
---

### Buzzkill

---

***Navigate***
```
sudo nano /etc/modprobe.d/audio-fix.conf
```
***Add***
```
options snd_hda_intel power_save=0
```
***Should return 0***
```
cat /sys/module/snd_hda_intel/parameters/power_save
```
