<h1 align="center">Office of Naval Research - DIALECT Project </h1>
<p align="center">
  <img src="https://user-images.githubusercontent.com/68829206/151713416-38d91e85-c7b0-463e-8a62-5c5f268e6739.png"/>
</p>

<h1 align="center">Communication Protocols Customization via Feature DIAgnosis, Lacing, Elimination, Cross-grafting, and Trimming </h1>
<p align="center">
<img src="https://user-images.githubusercontent.com/68829206/151620115-50a76a50-b9cc-4a4d-97af-d911bb4911eb.png"/>
</p>

# Motivation of this project
The implementations of network protocols are often "bloated" due to various users' needs and complex environment for deployment. The continual expansion of program features contribute to not only growing complexity but also increased the attack surface, making the maintenance of network protocol security very challenging. The goal of DIALECT is to create an automated tool that generates customized protocol binaries in large volume and in an unsupervised fashion.

# Composition of this project
In this project, we have proposed several approaches for automated customization and vulnerability detection of network protocols: CustomPro and yFuzz.

# CustomPro
In CustomPro, We adopt whole system emulation, dynamic tainting and symbolic execution to identify desired code from the original program binaries, then leverage binary rewriting techniques to create a customized program binary that only contains the desired functionalities.

# yFuzz
We have designed a stateful protocol fuzzer that aims to efficiently locate the vulnerabilities residing deep in the stateful protocols.

# VMs- Yfuzz & CustomPro
The VMs are ready to roll. Just open the VM using VMware and start to play. 
Password is space

1. yFuzz vm - https://drive.google.com/drive/folders/1kh-tGILQoA4mvs4ohwqV5EoBvvaSmUeC?usp=sharing
2. Source code- Yfuzz - https://github.com/yuroc0598/ProtocolCustomization/wiki/yFuzz
3. Custom pro vm - https://drive.google.com/drive/folders/1ONDJuIAKVTVUEzBUYJX5CUWoPleox83U?usp=sharing 
4. Source code- CustomPro - https://github.com/yuroc0598/ProtocolCustomization/wiki/CustomPro

# Papers - Conferences/ Journals
1. yFuzz: Digital Threats: Research and Practice (DTRAP)
2. CustomPro: EAI International Conference on Security and Privacy in Communication Networks (Securecomm 2019)
3. Hunting garbage collection: Proceedings of the 2020 Workshop on Forming an Ecosystem Around Software Transformation (FEAST '20)
4. MPD: EAI International Conference on Security and Privacy in Communication Networks (Securecomm 2021)
5. Verify-Pro: Proceedings of the IEEE Military Communications Conference (MILCOM 2022)
6. DAMgate: Proceedings of the 2017 Workshop on Forming an Ecosystem Around Software Transformation (FEAST '17)
7. TOSS: Proceedings of the 2018 Workshop on Forming an Ecosystem Around Software Transformation (FEAST '18)

# Papers
1. yFuzz: https://github.com/yuroc0598/ProtocolCustomization/blob/master/Publications%26Slides/Publications/yfuzz.pdf
2. CustomPro: https://www2.seas.gwu.edu/~tlan/papers/CP_SC_2019.pdf
3. Hunting garbage collection: https://www2.seas.gwu.edu/~tlan/papers/GC_FEAST_2020.pdf
4. MPD: https://arxiv.org/pdf/2110.03798.pdf
5. Verify-Pro:  https://arxiv.org/abs/2202.00500 
6. DAMgate: https://www2.seas.gwu.edu/~tlan/papers/DG_FEAST_2017.pdf
7. TOSS: https://www2.seas.gwu.edu/~tlan/papers/TOSS_FEAST_2018.pdf

### Repository overview 
    .
    ├── Papers                  # Papers submitted as part of the grant
    ├── Presentation_slides     # Presentation slides for the papers
    ├── Report_PJR              # Feedback (answered by the Dialect team)- Yfuzz & CustomPro
    ├── Yfuzz_CustomPro_PJR     # Yfuzz & CustomPro reports given by PJR Corps
    └── README.md               # All the links for papers, presentations, SSSS (TPCP) Material

# SSSS TPCP Presentation material
##  Tutorial at the TPCP Software Security Summer School (SSSS), 2020
https://drive.google.com/drive/folders/1oetQ9ahzRyHvMzvNBzwJ-wDc7oF3Wme5?usp=sharing

# Contact info
1. [Tian Lan](https://www2.seas.gwu.edu/~tlan/)
2. [Guru Venkataramani](https://www2.seas.gwu.edu/~guruv/)
