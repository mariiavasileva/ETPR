# ETPR
Estimation Techniques for Probabilistic Reachability

    // evaluating probability using simple ICDF QMC algorithm
    capd::interval evaluate_qmc();
    // evaluating CI using RQMC CLT algorithm
    capd::interval evaluate_rqmc_CLT();
    // evaluating CI using RQMC Agresti-Coull algorithm
    capd::interval evaluate_rqmc_AC();
    // evaluating CI using RQMC Willson algorithm
    capd::interval evaluate_rqmc_Will();
    // evaluating CI using RQMC Logit algorithm
    capd::interval evaluate_rqmc_Log();
    // evaluating CI using RQMC Anscombe algorithm
    capd::interval evaluate_rqmc_Ans();
    // evaluating CI using RQMC Arcsine algorithm
    capd::interval evaluate_rqmc_Arc();
    // evaluating CI using Qint algorithm
    capd::interval evaluate_Qint();
    // evaluating CI using all CI algorithms
    capd::interval evaluate_mixCI();
    // GP approximation
    capd::interval evaluate_GPmain();
