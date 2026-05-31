# Microsoft Band Dashboard

![Microsoft Band](mband.jpg)

This workspace now centers on the live Microsoft Band 2 dashboard and its data tooling.

## Main entry points

- `band2_dashboard.py`: live dashboard and session recorder
- `band2.py`: lower-level Band access helpers
- `band2_live.py`: live sensor streaming utilities
- `band2_probe_missing.py`: probe for less common sensors
- `BAND2_NOTAS.md`: operating notes and metric reference
- `BAND2_OOBE_USB_RUNBOOK.md`: OOBE / USB workflow notes

## Run the dashboard

```bash
python3 band2_dashboard.py 58:82:A8:CE:4E:C8
```

Open:

```text
http://127.0.0.1:8000
```

## Repository layout

- `emotions_inference_with_microsoft_band/`: original cloned repository kept as reference
- `recordings/`: session JSON files written by the dashboard

