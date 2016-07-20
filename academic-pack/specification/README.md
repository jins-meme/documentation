# Sensors
***
### Three-point Electrooculograpy Sensors
| Contents | Spec |
|----|----|
| Resolution | 12bit |
| Range(μV) | -1500 to 1500 |	
| Sensitivity(LSB/μV) | 1.37 |
| Electrode Materials | Stainless Steel (SUS316L) |
| Sampling Frequency<sup>[*2](#notes)</sup> | [Full mode](#full-mode-frequency) |
| | [Standard mode](#standard-mode-frequency) |
| | [Quatanion mode](#quaternion-mode-frequency) |

***

### Three-axis accelerometer sensors
| Contents | Spec |
|----|----|
| Resolution | 16bit |
| Range(g) | ±2, ±4, ±8, ±16 |
| Sensitivity(LSB/g) | 16384, 8192, 4096, 2048 |
| Zero-g offset | ±60mg |
| Differential nonlinearity | ±0.5% |
| Bandwidth(-3dB) | 4-4000Hz |

***

### Three-axis gyroscope sensors
| Contents | Spec |
|----|----|
| Resolution | 16bit |
| Range(dps) | ±250, ±500, ±1000, ±2500 |
| Sensitivity(LSB/dps) | 131, 65.5, 32.8, 16.4 |
| Zero-g offset | ±60mg |
| Differential nonlinearity | ±0.5%(25℃) |
| Bandwidth(-3dB) | 4-8000Hz |

***

## General
| Contents | Spec |
|----|----|
| Wireless | Bluetooth Low Energy |
| | Connectivity speed | 100Hz or 50Hz |
| Battery | Up to 16 hours |
| Power requirements | Supply voltage : 100V to 240V AC |
| | Supply frequency : 50Hz to 60Hz |
| Weight | Approx. 36g Wellington model (with dummy lenses) |

##### Notes
> *1 The product specifications may change without prior notification.

> <span style="font-size:0.5em">*2 Full mode: electrooculography sensors ON / accelerometer sensors ON / gyroscope sensors ON
Standard mode: electrooculography sensors ON / accelerometer sensors ON / gyroscope sensors OFF
Quaternion mode: electrooculography sensors OFF
</span>

[back↑](#hardware-specifications1)
***


# Software specifications & sample data download

## Designated viewer
| Contents | Spec |
|----|----|
| Software | Data Logger for Windows / Android |
| Connectivity | Bluetooth LE |
| System(PC) | OS : Microsoft Windows 8.1 64bit |
| | Processor : Inter Core i5 2.30GHz and above (Recommended Intel Core i7) |
| | Memory : At least 2GB (4GB recommended) |
| System Requirements(Smartphone) | OS : Android 4.4 |
| | Device : Nexus5 |

***
| Windows| Android |
|----|----|
| ![windows](https://meme-consumer-static.jins-meme.com/img/academic/specifications/img_viewer_windows.jpg?version=201605181100) | ![android](https://meme-consumer-static.jins-meme.com/img/academic/specifications/img_viewer_android.jpg?version=201605181100) |

***
### Download sample of CVS data : [Sample](https://jins-meme.com/download_common.php?f=acp_csvsample.xlsx)

***
[back↑](#three-point-electrooculograpy-sensors)
##### Full-mode-Frequency
| Sensor | Frequency |
|----|----|
| Electrooculography | 100Hz |
| Accelerometer | 100Hz |
| Gyroscope | 100Hz |
***
##### Standard-mode-Frequency
| Sensor | Frequency |
|----|----|
| Electrooculography sensor | 200Hz |
| Accelerometer sensor | 100Hz |
***
##### Quaternion-mode-Frequency
| Sensor | Frequency |
|----|----|
| Quaternion | 100Hz |

[back↑](#three-point-electrooculograpy-sensors)

***