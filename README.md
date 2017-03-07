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
