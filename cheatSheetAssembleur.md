# Registres x86 Cheat Sheet

## Registres généraux 32/64 bits :
| Nom   | Signification       | Utilité                               |
|-------|---------------------|---------------------------------------|
| EAX/RAX | Accumulateur      | Stocke les résultats de calculs      |
| EBX/RBX | Base              | Pointe vers des données dans la mémoire |
| ECX/RCX | Compteur          | Utilisé pour les boucles              |
| EDX/RDX | Données            | Souvent utilisé avec EAX pour les résultats étendus |
| ESI/RDI | Source/Destination | Pointeurs pour les opérations de chaînes |
| ESP/RSP | Pointeur de pile   | Gère la pile                          |
| EBP/RBP | Pointeur de base   | Pointe vers la base de la pile        |

## Registres de segment :
| Nom   | Signification | Utilité                   |
|-------|---------------|---------------------------|
| CS    | Code Segment  | Segment de code           |
| DS    | Data Segment  | Segment de données        |
| ES    | Extra Segment | Segment supplémentaire   |
| FS    | F Segment     | Utilisé pour des tâches spécifiques |
| GS    | G Segment     | Utilisé pour des tâches spécifiques |
| SS    | Stack Segment | Segment de pile           |

## Registres d'index :
| Nom   | Signification | Utilité                       |
|-------|---------------|-------------------------------|
| EIP/RIP | Instruction Pointer | Pointe vers l'instruction en cours d'exécution |
| EFLAGS/RFLAGS | Flags        | Stocke des indicateurs d'état |
| ST0-ST7 | Registres FPU | Utilisés pour les calculs en virgule flottante (x87 FPU) |
| XMM0-XMM15 | Registres SSE | Pour les opérations SIMD (Single Instruction, Multiple Data) |

## Registres de contrôle :
| Nom   | Signification | Utilité                    |
|-------|---------------|----------------------------|
| CR0-CR4 | Control Registers | Contrôle divers aspects du processeur |
| DR0-DR7 | Debug Registers | Utilisés pour le débogage |

## Registres de modèle de table :
| Nom   | Signification | Utilité                         |
|-------|---------------|---------------------------------|
| GDTR  | Global Descriptor Table Register | Pointe vers la table des descripteurs globaux |
| IDTR  | Interrupt Descriptor Table Register | Pointe vers la table des descripteurs d'interruption |
| LDTR  | Local Descriptor Table Register | Pointe vers la table des descripteurs locaux |
| TR    | Task Register | Utilisé pour la commutation de tâches |

## Registres de gestion de performances :
| Nom   | Signification | Utilité                             |
|-------|---------------|-------------------------------------|
| MSRs  | Model-Specific Registers | Contrôle des fonctionnalités spécifiques au modèle du processeur |
