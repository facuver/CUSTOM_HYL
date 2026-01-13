README for package: custom_hyl

custom_hyl is a top level controller:

1. Capture runs Continuously in Burst Mode
2. SR=2MHz, SSB=4x2+4x4 = 20bytes = 40MB/s peak
3. Bursts are triggered at 48Hz, TLEN=8192, avg rate: 8/40 * 40 = 8MB/s

Host data application acq400_stream streams data from port 4210

4. Port 4210 is nailed up for long duration.



