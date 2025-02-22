ingredients 0.3.5
----------------------------------------------------------------
* new feature [#29](https://github.com/ModelOriented/ingredients/issues/29). Feature importance now takes an argument `B` that replicates permutations `B` times and calculates average from drop loss.

ingredients 0.3.4
----------------------------------------------------------------
* `plotD3` now supports Ceteris Paribus Profiles.
* `feature_importance` now can take `variable_grouping` argument that assess importance of group of features
* fix in ceteris_paribus, now it handles models with just one variable
* fix [#27](https://github.com/ModelOriented/ingredients/issues/27) for multiple rows 
ingredients 0.3.3
----------------------------------------------------------------
* `show_profiles` and `show_residuals` functions extend Ceteris Paribus Plots.
* `show_aggreagated_profiles` is renamed to `show_aggregated_profiles`
* centering of ggplot2 title

ingredients 0.3.2
----------------------------------------------------------------
* added new functions `describe()` and `print.ceteris_paribus_descriptions()` for text based descriptions of Ceteris Paribus explainers
* `plot.ceteris_paribus_explainer` works now also for categorical variables. Use the `only_numerical = FALSE` to force bars

ingredients 0.3.1
----------------------------------------------------------------
* added references to PM VEE
* `partial_profiles()`, `accumulated_profiles()` and `conditional_profiles` for variable effects
* major changes in function names and file names

ingredients 0.3
----------------------------------------------------------------
* `ceteris_paribus_2d` extends classical ceteris paribus profiles
* `ceteris_paribus_oscillations` calculates oscilations for ceteris paribus profiles
* fixed examples and file names

ingredients 0.2
----------------------------------------------------------------
* `cluster_profiles` helps to identify interactions
* `partial_dependency` calculates partial dependency plots
* `aggregate_profiles` calculates partial dependency plots and much more

ingredients 0.1
----------------------------------------------------------------
* port of `model_feature_importance` and `model_feature_response` from `DALEX` to `ingredients`
* added tests
