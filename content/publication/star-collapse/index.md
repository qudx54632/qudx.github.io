---
title: "Publications in Star Collapse and Black Holes"
# authors:
#   - DQ
date: 2026-03-27
---

### Selected Publications

1. **Dongxue Qu**, Cong Zhang.  
   *Consistent Gauge Conditions for Dust-Shell Dynamics in Effective Quantum Gravity*.  
   arXiv:2603.24168 [gr-qc], 2026.  
   [PDF](https://arxiv.org/pdf/2603.24168) · [arXiv](https://arxiv.org/abs/2603.24168) · [Code](https://github.com/qudx54632/dust-shell-gauge-conditions) · [INSPIRE](https://inspirehep.net/literature/3134156)  
   _Cited by_: <span id="citecount1">updating…</span>

2. **Dongxue Qu**, Hongguang Liu.  
   *Quantum induced shock dynamics in gravitational collapse: insights from effective models and numerical frameworks*.  
   arXiv:2504.18462 [gr-qc], 2025.  
   [PDF](https://arxiv.org/pdf/2504.18462) · [arXiv](https://arxiv.org/abs/2504.18462) · [Code](https://github.com/qudx54632/Shock-wave-project) · [INSPIRE](https://inspirehep.net/literature/2915637)  
   _Cited by_: <span id="citecount2">updating…</span>

<script>
function updateCitations(id, inspireID) {
  fetch(`https://inspirehep.net/api/literature/${inspireID}`)
    .then(res => res.json())
    .then(data => {
      const count = data.metadata?.citation_count ?? "0";
      document.getElementById(id).innerText = count;
    })
    .catch(() => {
      document.getElementById(id).innerText = "N/A";
    });
}

updateCitations("citecount1", "3134156");
updateCitations("citecount2", "2915637");
</script>