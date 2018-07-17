# Protocol for Curating B10K Fossil Data for Analysis under the Fossilized Birth-Death Model

## Background

Information from the fossil record will be integrated with other types of data for divergence time estimation using the fossilized birth-death family of models.
With an FBD model, fossil sampling is modeled jointly with speciation and extinction in a process-based framework that includes extinct lineages.
This approach differs from more conventional node-calibration methods in that fossil species lineages are explicitly represented on the tree.
This more explicit and principled accounting of the process generating fossil data in extinct clades leads to more reliable and repeatable inferences about the entire diversification process, ultimately resulting in better divergence time estimates.

## The Model

Most recently, an extension of the FBD model has been developed that accounts for different modes of speciation, and allows for the direct analysis of fossil species stratigraphic range data ([Stadler et al. 2017](https://www.sciencedirect.com/science/article/pii/S002251931830119X)).
This model makes it easier to adapt an FBD analysis to the type of sampling data that is most commonly recorded by paleobiologists.
Only the ages of first and last fossil occurrence of each species are needed to apply this model.

## The Data

Ideally, data would be represented by stratigraphic ranges, the boundaries of which indicate the ages of the first and last occurrence of a species.

| Fossil Species Name | Min Age | Max Age | First Appearance  | Last Appearance | Citation | How Dated | Notes |
|-----------|----------------|---|---|---|---|---|---|
| Pachydyptes ponderosus | 34.5 | 36 | n/a | n/a |  Ksepka et al., 2012 | All known fossils of this species are all assigned to the Runangan NZ local stage, the bounds of which are used for the age range | A morphological matrix is available for this species (see Gavryushkina et al 2017)  |
| Pygoscelis grandis | 2.5 | 8.6 | 7.6(+-1.3) | 2.5-4.6 |  Walsh and Suárez 2006 | The oldest specimens are from the Bonebed Member of the Bahia Inglesia Fm. and are from below a layer dated to 7.6 ± 1.3 Ma, whereas younger specimens are estimated to be 2.5–4.6 Ma based on biostratigraphy | A morphological matrix is available for this species (see Gavryushkina et al 2017)  |
