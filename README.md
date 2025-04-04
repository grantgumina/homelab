## Overview


## Architecture Diagram

```
Internet  
   |  
+---------+  
| Router  |  
+---------+  
   |  
+--------------------+  
| TP-Link W6000 Mesh |  
+--------------------+  
   |  
   |-- 4U Gaming PC (Racked)  
   |  
   |-- 3U Proxmox Server (Hyperconverged)  
       |  
       |-- VM #1 (Containers)  
       |    |-- Plex  
       |    |-- Deluge  
       |    |-- Sonarr  
       |    |-- Radarr  
       |    |-- NZBGet  
       |    |-- Gluetun  
       |    |-- AdGuard Home  
       |    |-- HandBrake  
       |  
       |-- VM #2 (Home Assistant)  
       |    |-- 3 Smart Bulbs  
       |    |-- Smart Fan (Zwift)  
       |  
       |-- VM #3 (TrueNAS)  
            |-- 40TB Shared Storage  
```

## Hardware

### Hyperconverged Server
- [AMD Ryzen 7 9700X 3.8 GHz 8-Core Processor](https://www.amd.com/en/products/cpu/amd-ryzen-7-9700x)  
- [Noctua NH-L9A-AM5 33.84 CFM CPU Cooler](https://noctua.at/en/nh-l9a-am5)  
- [ASRock B850M-X WiFi Micro ATX AM5 Motherboard](https://www.asrock.com/mb/AMD/B850M-X%20WiFi/)  
- [G.Skill Ripjaws M5 RGB 96 GB (2 x 48 GB) DDR5-5200 CL40 Memory](https://www.gskill.com/product/165/398/1702978834/F5-5200J4048A48GX2-RS-%7C-Ripjaws-M5-RGB)  
- [Samsung 990 EVO Plus 2 TB M.2-2280 PCIe 5.0 X2 NVMe SSD](https://www.samsung.com/semiconductor/minisite/ssd/product/consumer/990-evo/)  
- 4x Refurbished 10TB Drives
- Sliger CX3 702
- [Corsair RM750x (2024) 750 W Fully Modular ATX Power Supply](https://www.corsair.com/us/en/p/psu/cp-9020278-na/rm750x-fully-modular-750-watt-80-plus-gold-atx-power-supply-black)  
- [SXTAIGOOD SAS3008 AOC-S3008L-L8E 9300-8I IT-Mode HBA JBOD PCI-E 3.0 SATA/SAS 8-Port SAS3 12Gb/s ZFS FreeNAS unRAID + 2x SFF-8643 SATA Cables](https://www.amazon.com/dp/B0C3D2ZV8L)  


### Gaming PC
- [Intel Core i3-6100 3.7 GHz Dual-Core Processor](https://pcpartpicker.com/product/hV7CmG/intel-cpu-bx80662i36100)
- [MSI H110M Pro-VD Micro ATX LGA1151 Motherboard](https://pcpartpicker.com/product/bPVBD3/msi-motherboard-h110mprovd)
- [Crucial Ballistix Sport LT 8 GB (2 x 4 GB) DDR4-2400 CL16 Memory](https://pcpartpicker.com/product/9yKhP6/crucial-memory-bls2k4g4d240fsc)
- [Western Digital Caviar Blue 250 GB 3.5" 7200 RPM Internal Hard Drive](https://www.amazon.com/dp/B000Q84G5Q?tag=pcpapi-20&linkCode=ogi&th=1&psc=1)	
- [Samsung 850 Evo 500 GB 2.5" Solid State Drive](https://pcpartpicker.com/product/FrH48d/samsung-internal-hard-drive-mz75e500bam)
- [MSI GT OC GeForce GTX 1060 3GB 3 GB Video Card](https://pcpartpicker.com/product/4Np323/msi-geforce-gtx-1060-3gb-3gb-oc-video-card-geforce-gtx-1060-3gt-oc)
- [Fractal Design Core 1000 USB 3.0 MicroATX Mid Tower Case](https://pcpartpicker.com/product/KPw323/fractal-design-case-fdcacore1000usb3bl)
- [EVGA 500 W1 500 W 80+ Certified ATX Power Supply](https://pcpartpicker.com/product/XCjG3C/evga-500-w1-500-w-80-certified-atx-power-supply-100-w1-0500-kr)
