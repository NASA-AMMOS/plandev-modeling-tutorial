# Mission Modeling Tutorial

This repo houses the simple on-board spacecraft solid state recorder model that you will build as part of [PlanDev's modeling tutorial](https://nasa-ammos.github.io/plandev-docs/tutorials/mission-modeling/introduction/).
While we recommend you go through the tutorial, this model also serves as an example you can use to jump start your own modeling efforts.
The model includes a resource that tracks recording rate (`RecordingRate`) and a number of different resources that show different ways in which you can integrate rate to get data volume over time (`SSR_Volume_*`).
A couple of different style data collection activities (`CollectData`, `ChangeMagMode`) are also included to trigger recording rate changes.

If you don't want to pull down and build this repo, but still want to try out the model, you can use the pre-built [missionmodel.jar](missionmodel.jar) and upload it directly to PlanDev.
If you do want to compile a jar for this model yourself, the instructions outlined in the [mission model template repo](https://github.com/NASA-AMMOS/plandev-mission-model-template?tab=readme-ov-file#plandev-mission-model-template) should work here as well.

