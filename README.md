Fragment-friendly ZXing
=======================

We have a need to embed QR code scanning and generation in an
Android 4.0 and above mobile app. The internals of the ZXing
scanner meet our needs perfectly (and we want to continue
getting upstream changes/enhancements) but the integration by
Intent does not meet our needs; we want to customize the UI
significantly, which ZXing does not support, and most of the
tutorials on this point seem to involve a lot of cut
and paste coding.

This fork has the object of tracking ZXing core closely (by
pulling upstream) and maintaining a legacy-free set of
barcode reader components that are suitable for integrating
ZXing core into Android 4.0 and above mobile apps.

The fork is new; integration details to land here once we
feel it is sufficiently stabilized. To pitch in, send a PR or
contact rob.heittman@solertium.com.
