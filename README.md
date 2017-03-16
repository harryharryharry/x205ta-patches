# x205ta-patches
fn-brightness-hack.patch:
adds support for brightness fn-keys

pinctrl-baytrail-intel.patch:
reverse patch the following commit
https://www.spinics.net/lists/linux-gpio/msg18340.html
to avoid breaking the internal keyboard

i915-prevent-cstate-freezes.patch:
Prevent c-state freezes without the use of a intel_idle.max_cstate kernel boot parameter

brcmfmac-fix-incorrect-event-channel-deduction.patch:
fix brcmfmac 5ghz-band wifi speeds 


headphones-halfway-fix.patch:
Some people mentioned they had trouble getting headphones to work when fully inserted. According to ederlezi2 at ubuntuforums this is solved by reverting this patch:
https://github.com/plbossart/sound/commit/320c60f28bfac6a95e1f8b092250e1879d98651e
