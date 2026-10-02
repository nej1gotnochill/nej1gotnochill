<p align="center">
  <img src="./BANNER.png" width="90%">
</p>

<table>
<tr>
<td><b><font color="#c084fc">Convex Optimization Engineer.</font></b> Building mathematical software that measurably runs faster.</td>
<td><a href="https://www.linkedin.com/in/divyansh-lalotra-89145137a/">LinkedIn</a> · <a href="https://github.com/nej1gotnochill">GitHub</a> · <a href="https://leetcode.com/u/nej1gotnochill/">LeetCode</a></td>
</tr>
</table>

I work where mathematical software meets the machine — canonicalization pipelines, solver interfaces, and the benchmarking infrastructure that tells maintainers whether a change actually made things faster.

## <font color="#c084fc">Open Source, Engineering & Programs</font>

- **[cvxpy](https://github.com/cvxpy/cvxpy)** [Open Source Developer](https://github.com/cvxpy/cvxpy/pulls?q=is%3Apr+author%3Anej1gotnochill) — added dual variables to `ConstantSolver` for feasible constant problems ([#3505](https://github.com/cvxpy/cvxpy/pull/3505), merged) and isolated OR-Tools tests from HiGHS to prevent native symbol conflicts ([#3508](https://github.com/cvxpy/cvxpy/pull/3508), merged)
- **[cvxpy](https://github.com/cvxpy/cvxpy)** [Tuple-Axis Norms](https://github.com/cvxpy/cvxpy/pull/3539) — tuple-axis support in `norm()` plus an N-D `p=2` SOC canonicalization fix, including a per-fiber coordinate-mapping bug that `keepdims=True` exposed while value-level assertions stayed tautological ([#3539](https://github.com/cvxpy/cvxpy/pull/3539))
- **[OpenMS](https://github.com/OpenMS/OpenMS)** [Open Source Developer](https://github.com/OpenMS/OpenMS/pulls?q=is%3Apr+author%3Anej1gotnochill) — built the project's first benchmarking layer for [Issue #8788](https://github.com/OpenMS/OpenMS/issues/8788): a gated `ENABLE_BENCHMARK_TESTING` CMake option, benchmark test directory, and CTest registration ([#9839](https://github.com/OpenMS/OpenMS/pull/9839))
- **[OpenMS-benchmarking](https://github.com/OpenMS/OpenMS-benchmarking)** [Benchmarking Infrastructure](https://github.com/OpenMS/OpenMS-benchmarking) — CI that builds OpenMS from a pinned SHA, runs DDA and OpenSwath DIA benchmarks, and reports wall time, CPU time, and peak RSS against a stored baseline. Contributed the v2 results schema with automatic v1 promotion, the benchmark-agnostic report renderer, the OpenSwath DIA benchmark and real comparison baseline, package-mode runtime, and the nightly benchmark loop ([#3](https://github.com/OpenMS/OpenMS-benchmarking/pull/3), [#4](https://github.com/OpenMS/OpenMS-benchmarking/pull/4), [#5](https://github.com/OpenMS/OpenMS-benchmarking/pull/5))
- **[Netra](https://github.com/nej1gotnochill/FluxShieldMLPipeline)** [ML Security](https://github.com/nej1gotnochill/FluxShieldMLPipeline) — passive network threat-detection platform: a leakage-aware DDoS detector validated under a strictly capture-disjoint protocol (Precision 0.999998, Recall 0.997849, FPR 0.00018 on 448k unseen flows) plus a streaming multi-threat service with causal early-detection windows
- **[cyberworld](https://github.com/SIH-2026-SSSVBT/Cyber_World)** [Predictive SOC](https://github.com/SIH-2026-SSSVBT/Cyber_World) — turns a SPAN feed into a live host graph with ATT&CK-aware risk forecasting, built on PyTorch temporal-graph models (TGN) for attack-evolution prediction
- **[HWSS-ML](https://github.com/nej1gotnochill/FluxShieldMLPipeline)** [Research](https://github.com/nej1gotnochill/FluxShieldMLPipeline) — intelligent authentication research combining ensemble risk scoring with SHAP explainability, focused on adversarial robustness and concept drift; volatility forecasting work spanning HARNet, GARCH, and gradient-boosted models with sentiment features

<div align="center">

<h2><font color="#c084fc">Open Source Development</font></h2>

---

Active upstream contributions to open-source optimization and scientific-computing software.

</div>

<table>
<tr>
<td align="center" width="50%">

<img src="./cvxpy-logo.png" alt="CVXPY" width="130">

<br><br>

<b><font color="#c084fc">CVXPY</font></b><br>
<font size="small">Open Source Developer</font><br>
<a href="https://github.com/cvxpy/cvxpy/pull/3505">#3505</a> &middot; <a href="https://github.com/cvxpy/cvxpy/pull/3508">#3508</a> &middot; <a href="https://github.com/cvxpy/cvxpy/pull/3539">#3539</a>

</td>
<td align="center" width="50%">

<img src="./openms-logo.png" alt="OpenMS" width="170">

<br><br>

<b><font color="#c084fc">OpenMS</font></b><br>
<font size="small">Open Source Developer</font><br>
<a href="https://github.com/OpenMS/OpenMS/issues/8788">#8788</a> &middot; <a href="https://github.com/OpenMS/OpenMS/pull/9839">#9839</a>

</td>
</tr>
</table>

## <font color="#c084fc">Tech Stack</font>

<table>
<tr>
<td align="center" width="50%" valign="top">

<b><font color="#c084fc">Languages</font></b><br><br>
<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python">
<img src="https://img.shields.io/badge/C++-00599C?style=flat-square&logo=c%2B%2B&logoColor=white" alt="C++">
<img src="https://img.shields.io/badge/R-276DC3?style=flat-square&logo=r&logoColor=white" alt="R">
<img src="https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white" alt="Bash">
<img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript">

</td>
<td align="center" width="50%" valign="top">

<b><font color="#c084fc">Convex Optimization</font></b><br><br>
<img src="https://img.shields.io/badge/CVXPY-0A5CA8?style=flat-square&logo=python&logoColor=white" alt="CVXPY">
<img src="https://img.shields.io/badge/HiGHS-E8734A?style=flat-square&logoColor=white" alt="HiGHS">
<img src="https://img.shields.io/badge/SCS-1F6FEB?style=flat-square&logoColor=white" alt="SCS">
<img src="https://img.shields.io/badge/Clarabel-3B82F6?style=flat-square&logoColor=white" alt="Clarabel">
<img src="https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white" alt="NumPy">
<img src="https://img.shields.io/badge/SciPy-8CAAE6?style=flat-square&logo=scipy&logoColor=white" alt="SciPy">

</td>
</tr>
<tr>
<td align="center" valign="top">

<b><font color="#c084fc">GPU &amp; Inference</font></b><br><br>
<img src="https://img.shields.io/badge/CUDA-76B900?style=flat-square&logo=nvidia&logoColor=white" alt="CUDA">
<img src="https://img.shields.io/badge/SGLang-a855f7?style=flat-square&logoColor=white" alt="SGLang">

</td>
<td align="center" valign="top">

<b><font color="#c084fc">ML &amp; Systems</font></b><br><br>
<img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white" alt="PyTorch">
<img src="https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white" alt="TensorFlow">
<img src="https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white" alt="scikit-learn">
<img src="https://img.shields.io/badge/XGBoost-237451?style=flat-square&logo=xgboost&logoColor=white" alt="XGBoost">
<img src="https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white" alt="pandas">

</td>
</tr>
<tr>
<td align="center" valign="top">

<b><font color="#c084fc">Platform &amp; Tooling</font></b><br><br>
<img src="https://img.shields.io/badge/Linux-F58536?style=flat-square&logo=linux&logoColor=white" alt="Linux">
<img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white" alt="Git">
<img src="https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white" alt="GitHub Actions">
<img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker">
<img src="https://img.shields.io/badge/CMake-064F8C?style=flat-square&logo=cmake&logoColor=white" alt="CMake">
<img src="https://img.shields.io/badge/Nextflow-3A3F3A?style=flat-square&logo=nextflow&logoColor=white" alt="Nextflow">

</td>
<td align="center" valign="top">

<b><font color="#c084fc">Practice</font></b><br><br>
<img src="https://img.shields.io/badge/pytest-0A9EDC?style=flat-square&logo=pytest&logoColor=white" alt="pytest">
<img src="https://img.shields.io/badge/Ruff-D7DCFB?style=flat-square&logo=ruff&logoColor=white" alt="Ruff">
<img src="https://img.shields.io/badge/cargo-f59C1?style=flat-square&logo=rust&logoColor=white" alt="Cargo">
<img src="https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white" alt="Jupyter">

</td>
</tr>
</table>

## <font color="#c084fc">GitHub Stats</font>

<p align="center">
<img src="https://github-readme-stats.vercel.app/api?username=nej1gotnochill&show_icons=true&theme=midnight-purple" alt="GitHub Stats" width="430">
<img src="https://github-readme-streak-stats.herokuapp.com/?user=nej1gotnochill&theme=midnight-purple" alt="GitHub Streak" width="430">
</p>

<p align="center">
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=nej1gotnochill&layout=compact&theme=midnight-purple" alt="Top Languages" width="330">
</p>
