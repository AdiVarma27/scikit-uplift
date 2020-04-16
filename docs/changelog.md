# Release History

## Legend for changelogs

* 🔥 something big that you couldn’t do before.
* 💥 something that you couldn’t do before.
* 📝 a miscellaneous minor improvement.
* 🔨 something that previously didn’t work as documentated – or according to reasonable expectations – should now work.
* ❗️ you will need to change your code to have the same effect in the future; or a feature will be removed in the future.

## Version 0.1.0
*In development*

### [sklift.models](https://scikit-uplift.readthedocs.io/en/latest/api/models.html)

* 📝 Fix typo in [TwoModels](https://scikit-uplift.readthedocs.io/en/latest/api/models.html#sklift.models.models.TwoModels) docstring by [@spiaz](https://github.com/spiaz).
* 📝 Improve docstrings and add references to all approaches.

### [sklift.metrics](https://scikit-uplift.readthedocs.io/en/latest/api/metrics.html)

* 💥 Add [treatment_balance_curve](https://scikit-uplift.readthedocs.io/en/latest/api/metrics.html#sklift.metrics.metrics.treatment_balance_curve) by [@spiaz](https://github.com/spiaz).
* ❗️ The metrics `auuc` and `auqc` are now respectively renamed to [uplift_auc_score](https://scikit-uplift.readthedocs.io/en/latest/api/metrics.html#sklift.metrics.metrics.uplift_auc_score) and [qini_auc_score](https://scikit-uplift.readthedocs.io/en/latest/metrics.html#sklift.metrics.metrics.qini_auc_score). So, `auuc` and `auqc` will be removed in 0.2.0.

### [sklift.viz](https://scikit-uplift.readthedocs.io/en/latest/api/viz.html)

* 💥 Add [plot_treatment_balance_curve](https://scikit-uplift.readthedocs.io/en/latest/api/viz.html#sklift.viz.base.plot_treatment_balance_curve) by [@spiaz](https://github.com/spiaz).
* 📝 fix typo in [plot_uplift_qini_curves](https://scikit-uplift.readthedocs.io/en/latest/api/viz.html#sklift.viz.base.plot_uplift_qini_curves) by [@spiaz](https://github.com/spiaz).

### Miscellaneous

* ❗️ Remove sklift.preprocess submodule.
* 💥 Add compatibility of tutorials with colab and add colab buttons by [ElMaxuno](https://github.com/ElMaxuno).
* 💥 Add Changelog.
* 📝 Change the documentation structure. Add next pages: [Tutorials](https://scikit-uplift.readthedocs.io/en/latest/tutorials.html), [Release History](https://scikit-uplift.readthedocs.io/en/latest/changelog.html) and [Hall of fame](https://scikit-uplift.readthedocs.io/en/latest/hall_of_fame.html).