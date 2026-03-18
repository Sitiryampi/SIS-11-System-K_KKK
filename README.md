SIS-11 (Spatial Impossibility System)
Author: Sitiryampi
A formal system exploring limits of definability via multi-dimensional encoding.
Overview
SIS-11 (Spatial Impossibility System) is a formal system based on ZFC, designed to study limits of definability via 11-dimensional formula encoding. It introduces a structured way to analyze how syntactic complexity relates to definability.
Definition
In SIS-11, numbers are “11D-definable” if there exists a formula φ(x₁…x₁₁) of bounded length that encodes a unique vector of 11 syntactic parameters (such as number of quantifiers, nesting depth, logical operators, and other structural features).
The encoding function is defined via prime factorization:
Enc(x₁…x₁₁) = 2^x₁ · 3^x₂ · 5^x₃ · 7^x₄ · 11^x₅ · 13^x₆ · 17^x₇ · 19^x₈ · 23^x₉ · 29^x₁₀ · 31^x₁₁
Hierarchy
The system includes a hierarchy of theories:
SIS₀ = ZFC
SISₙ₊₁ = SISₙ + Con(SISₙ)
SIS_ω = ⋃ SISₙ
This hierarchy enables meta-diagonalization and prevents certain numbers from being definable at any finite stage.
K_KKK (Kafka’s Kitty Scratcher)
K_KKK is a meta-diagonalizing number defined as exceeding all 11D-definable numbers within the system:
K_KKK = MaxDef₁₁(SIS_ω) + 1
It defines a boundary of definability within SIS-11.
Example Construction
Vector:
(1000, 500, 700, 300, 400, 200, 100, 50, 25, 10, 5)
Encoded number:
n_KKK = 2^1000 · 3^500 · 5^700 · 7^300 · 11^400 · 13^200 · 17^100 · 19^50 · 23^25 · 29^10 · 31^5
Full Text
Full formal description, definitions, and extended explanation:
https://docs.google.com/document/d/1-AZxk0ye__AiCbSkjYpi30BNxvaRNuZLcTwo-V9SUOU/edit?usp=drivesdk
Notes
This work was independently developed. An AI assistant was used only to help organize and clarify the presentation of the text.
Discussion
Feedback, corrections, and discussion are welcome.
Can similar meta-diagonalizing constructions be defined under alternative encoding schemes?
