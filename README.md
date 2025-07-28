```mermaid
graph TD;

%% ======== TITULOS DE SEMESTRES ========
T1["1° AÑO – 1° Semestre"]:::titulo
T2["1° AÑO – 2° Semestre"]:::titulo
T3["2° AÑO – 1° Semestre"]:::titulo
T4["2° AÑO – 2° Semestre"]:::titulo
T5["3° AÑO – 1° Semestre"]:::titulo
T6["3° AÑO – 2° Semestre"]:::titulo
T7["4° AÑO – 1° Semestre"]:::titulo
T8["4° AÑO – 2° Semestre"]:::titulo
T9["5° AÑO – Práctica"]:::titulo

%% ======== 1° AÑO – 1° SEMESTRE ========
A1[Anatomía del Sistema Locomotor]:::s1
B1[Biología]:::s1
C1[Computación Básica]:::s1
D1[Comunicación Efectiva]:::s1
E1[Introducción a la Kinesiología]:::s1
F1[Nivelación de Competencias I]:::s1

%% ======== 1° AÑO – 2° SEMESTRE ========
A2[Anatomía Funcional]:::s2
B2[Bioquímica]:::s2
G1[Información y Construcción del Conocimiento]:::s2
H1[Inglés I]:::s2
I1[Matemáticas]:::s2
F2[Nivelación de Competencias II]:::s2

A1 --> A2
B1 --> B2
F1 --> F2

%% ======== 2° AÑO – 1° SEMESTRE ========
K1[Anatomofisiología de Sistemas]:::s3
J1[Biomecánica]:::s3
N1[Estadística y Epidemiología]:::s3
H2[Inglés II]:::s3

B2 --> K1
A2 --> J1
H1 --> H2

%% ======== 2° AÑO – 2° SEMESTRE ========
M1[Fisiología del Ejercicio]:::s4
M2[Fisiopatología]:::s4
L1[Motricidad Humana I]:::s4
O1[Psicología General]:::s4
P1[Universidad y Entorno]:::s4

K1 --> M1
K1 --> M2
J1 --> L1

%% ======== 3° AÑO – 1° SEMESTRE ========
Q1[Motricidad Humana II]:::s5
H3[Inglés III]:::s5

L1 --> Q1
H2 --> H3

%% ======== 3° AÑO – 2° SEMESTRE ========
R1[Kinesiología Musculoesquelética]:::s6
R2[Seminario Act. Musculoesquelética]:::s6
S1[Investigación y Gestión I]:::s6

Q1 --> R1
Q1 --> R2
N1 --> S1

%% ======== 4° AÑO – 1° SEMESTRE ========
U1[Kinesiología Cardiorrespiratoria]:::s7
U2[Seminario Act. Cardiorrespiratoria]:::s7
T1[Investigación y Gestión II]:::s7

M1 --> U1
M1 --> U2
S1 --> T1

%% ======== 4° AÑO – 2° SEMESTRE ========
V1[Neurokinesiología]:::s8
V2[Seminario Act. Neurokinesiología]:::s8
W1[Investigación y Gestión III]:::s8

R1 --> V1
R1 --> V2
T1 --> W1

%% ======== 5° AÑO – PRÁCTICA ========
P[Práctica Profesional Guiada]:::s9

%% Conexión de todos los ramos a práctica según requisitos
A1 --> P
B1 --> P
C1 --> P
D1 --> P
E1 --> P
F1 --> P
A2 --> P
B2 --> P
F2 --> P
G1 --> P
H1 --> P
H2 --> P
H3 --> P
I1 --> P
J1 --> P
K1 --> P
L1 --> P
M1 --> P
M2 --> P
N1 --> P
O1 --> P
P1 --> P
Q1 --> P
R1 --> P
R2 --> P
S1 --> P
T1 --> P
U1 --> P
U2 --> P
V1 --> P
V2 --> P
W1 --> P

%% ======== ESTILOS ========
classDef titulo fill:#fff,stroke:#c94f7c,stroke-width:2px,font-size:18px,font-weight:bold;
classDef s1 fill:#f9d7e3,stroke:#c94f7c,stroke-width:2px;
classDef s2 fill:#f8c1d8,stroke:#c94f7c,stroke-width:2px;
classDef s3 fill:#f6abc9,stroke:#c94f7c,stroke-width:2px;
classDef s4 fill:#f497b9,stroke:#c94f7c,stroke-width:2px;
classDef s5 fill:#f183aa,stroke:#c94f7c,stroke-width:2px;
classDef s6 fill:#ee6e9b,stroke:#c94f7c,stroke-width:2px;
classDef s7 fill:#ea598c,stroke:#c94f7c,stroke-width:2px;
classDef s8 fill:#e6447d,stroke:#c94f7c,stroke-width:2px;
classDef s9 fill:#e1306e,stroke:#c94f7c,stroke-width:2px;
