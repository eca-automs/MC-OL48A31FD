# MC-OL48A31FD

Schema quadro elettrico per ascensore serie `mcpx`. Impianto oleodinamico con emergenza 48VDC, gestione emendamento A3, fossa e testata ridotta.

Puoi trovare il repository dello schema su
<a href="https://github.com/eca-automs/MC-OL48A31FD" target="_blank">GitHub</a>.

### Scheda controllo
MCPX2015-SMD - PER16B-SMD

###### Firmware
[P](https://docs.ecaq.in/it/info/mcpx-board-manual-p).

### Tipo impianto
Oleodinamico.

### Manovra
Universale.

### Collegamento vano / cabina
| Vano     | Cabina     |
| :------------- | :------------- |
| parallelo | parallelo |


### Operatore porte
* manuale
* automatico 48VDC

### Avviamento / controllo motore
* diretto
* stella-triangolo
* soft-starter (con soft-starter SMS-start)

### Potenza massima motore / taglie compatibili
##### Avviamento diretto
| Taglia | Potenza |
| :------------- | :------------- |
| S20 | 8CV-230VAC/15CV-400VAC |
| S30 | 10CV-230VAC/17CV-400VAC |

#### Avviamento stella-triangolo
| Taglia | Potenza |
| :------------- | :------------- |
| S40 | 14CV-230VAC/22CV-400VA |
| S50 | 17CV-230VAC/28CV-400VAC |

#### Avviamento soft-starter
| Taglia | Potenza |
| :------------- | :------------- |
| S40 | 10CV-230VAC/20CV-400VAC |
| S50 | 13CV-230VAC/25CV-400VAC |

### Allarme
* 12VDC
* legge 13

### Emergenza
Emergenza con riapertura porte tramite gruppo batterie 48VDC.

### Emendamento A3
Gestione con doppia valvola discesa controllata da boxA3 (SMS).

### Fossa / testata ridotta
* gestione fossa ridotta
* gestione testata ridotta
