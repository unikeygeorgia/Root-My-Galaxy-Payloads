# q7q-F966U1UEUCCZIH

Samsung Galaxy Z Fold7 `SM-F966U1`, XAA/OYM, Android 17 build
`CP2A.260605.016.F966U1UEUCCZIH`.

The profile is for the exact `6.6.127-android15-8-peeee058-abogkiF966USQUCCZIH-4k`
kernel. `target.h` overrides every image-relative symbol that differs from the
older Fold7 6.6.98 profile. The structure geometry is confirmed from the
embedded CZIH BTF; `p0_fingerprint.h` is generated from the exact raw kernel
Image with the repository fingerprint generator.

The profile is statically verified. Runtime tracefs event ID, payload execution,
and root handoff still require the user's device over USB.
