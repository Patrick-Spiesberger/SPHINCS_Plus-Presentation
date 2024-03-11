# SPHINCS+ Presentation

SPHINCS+ is a stateless and hash-based signature scheme popularised by the NIST post-quantum competition. As an improvement on SPHINCS, it also consists of several stateful components, such as WOTS+, and improves both security and efficiency. Its security is based on the difficulty of finding pre-images for the hash functions, which is why its security will not be massively affected by quantum computers. SPHINCS+ uses very small public keys, but generates large signatures that are often unwieldy in practice. This short summary is intended to give an overview of the concepts of SPHINCS+.

The rights to the template for this presentation belong to the KASTEL: Cryptography and Security Group (https://crypto.kastel.kit.edu/templates.php). Additional sources are annotated on the slide. This is student work and may therefore not fully meet academic standards.


## References
[1] Jean-Philippe Aumasson and Guillaume Endignoux. Improving Stateless Hash-Based Signatures. 2017. url: https://eprint.iacr.org/2017/933.
[2] Daniel J. Bernstein et al. “SPHINCS: Practical Stateless Hash-Based Signatures”. In: ed. by Elisabeth Oswald and Marc Fischlin. 2015. doi: 10.1007/978-3-662-46800-5_15. url: https://doi.org/10.1007/978-3-662-46800-5_15.
[3] Daniel J. Bernstein et al. “The SPHINCS+ Signature Framework”. In: 2019. doi: 10.1145/3319535.3363229. url: https://doi.org/10.1145/3319535.3363229.
[4] COSIC seminar "Introduction to Hash Based Signatures" (John Kelsey, KU Leuven and NIST). last visited: 14.12.2023. url: https://youtu.be/jiU0ICoiPI0?si=mbZRousIb2wnp1mi.
[5] Andreas Hülsing et al. “SPHINCS+C: Compressing SPHINCS+ With (Almost) No Cost”. In: IEEE, 2023, pp. 1435–1453. doi: 10.1109/SP46215.2023.10179381. url: https://doi.org/ 10.1109/SP46215.2023.10179381.
[6] Ruben Niederhagen, Johannes Roth, and Julian Wälde. “Streaming SPHINCS+ for Embedded Devices Using the Example of TPMs”. In: 2022. doi: 10.1007/978-3-031-17433-9_12.
[7] Sizing Up Post-Quantum Signatures. last visited: 14.12.2023. url: https://blog.cloudflare. com/sizing-up-post-quantum-signatures/.
[8] SPHINCS+ – The smaller SPHINCS. last visited: 14.12.2023. url: https://huelsing.net/wordpress/?p=558.
[9] Kaiyi Zhang, Hongrui Cui, and Yu Yu. “SPHINCS-α: A Compact Stateless Hash-Based Signature Scheme”. In: IACR Cryptol. ePrint Arch. (2022), p. 59.
