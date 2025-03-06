---
title: "Déploiement de SNN sur SoC RISC-V"
date: 2023-09-20
tags: ["SNN", "RISC-V", "TinyML"]
draft: false
---

## Abstract
Notre méthode hybride SNN/QNN permet une réduction de 72% de la consommation énergétique sur des benchmarks MLPerf Tiny...

{{< highlight c >}}
// Exemple de code d'optimisation
void snn_inference() {
  riscv_pulp_io_write(SNN_CFG, 0x1A3F);
  while(!(riscv_pulp_io_read(SNN_STATUS) & 0x1));
}
{{< /highlight >}}
