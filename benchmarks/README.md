# Reproducible performance comparison

No matched vanilla-versus-Karvo results are published yet. Do not substitute build success or a rendering microbenchmark for measured gameplay performance.

1. Record hardware, OS/driver, display resolution, Minecraft and Java versions, RAM allocation, world/server, render/simulation distance, graphics settings, resource packs, shaders and optional mods. Disclose every difference.
2. Use the same saved world, route/camera movement, item-frame count/content and entity load. Compare the same Minecraft version. Test vanilla and Karvo separately, without other game instances or recording software unless both runs use it.
3. Warm up for two minutes, then record at least 60 seconds of frame times. Alternate baseline/Karvo order across at least three pairs. Keep raw samples and metadata. Separate empty frames, normal items and maps into separate scenarios.
4. Export JSON as {"metadata":{"scenario":"...","minecraft":"...","hardware":"...","settings":"..."},"frameTimesMs":[...]} for each run. Use an external frame-time recorder or correctly measured client instrumentation; do not convert sparse FPS labels into frame-time distributions.
5. Run node benchmarks/compare.cjs baseline.json karvo.json. Report each run plus the median across repeated runs; publish limitations and any regression. 1% low here means 1000 divided by the average slowest 1% frame times, not the first percentile of sampled FPS.

Before sharing metadata remove personal paths, server IPs, UUIDs and account details. Results are not a promise of performance on other computers.
