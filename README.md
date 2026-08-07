# atvhunt tile sweep

One account of a 4-account tiled full-range sweep of atvhunt.com.
Window w = [w*768000, (w+1)*768000); account k owns id %% 4 == k; shard s takes that
account ids[s::256] = exactly 750 ids. Coverage is by construction and proven by
per-state accounting in scripts/atvhunt_close.py.

Source of record: https://github.com/ahmerfr/SupremeMotors (branch atvhunt-crawl).
