Environments breakout session
==

### Things to talk about
- Not re-inventing the wheel
- Reproducibility of compute environment (e.g. HPC / Spark, Containers)
- Re-run experiment with different parameters / algorithms (repeatability). Can users / researchers do this themselves?
- Modularising the environment (e.g. code and environment published but then code is changed to require aditional libraries / change envrironment)

### Parallel vs serial processing
-   Using traditional HPC clusters requires knowing a lot of shell, job managers etc.
-   Wikipedia use Jupyter Hub to run python scripts to do scripted checks on Wikipedia.
-   People write serial code for their laptop. How to take advantage of parallel power of cloud / GPU / cluster etc?
-   Do researchers write data parallel code (i.e. run pipeline across data)?
-   Some researchers learn to parallelise parameter sweeps. Often initially manually starting a process / session per parameter set. When shown option of using job manager (e.g. GridEngine) or scripting sweep, researchers do see the benefits. 
-   Data Scientists will be familiar with Spark and be able to easily parallelise using this. How many researchers use tools like Spark? How easy would it be for most researchers to learn to code their problem declaratively in Spark?

### Minimising pain moving from own computer to cluster / cloud / GPU
 - Teaching people how to do something vs providing tooling to do it for them.
 - Providing automated tooling can be tricky due to "forking paths" problem.
 - Need to minimise things people need to learn / time people need to spend before getting on with their work. E.g. getting people to dockerise their code from the start is not going to happen.
 - Can we easily "uplift" people's code to dockerise it at the point they want to run elsewhere (e.g. repo2docker)

### Reproducibility
- Shouldn't set bar too high. Having it reproducible today is massively beneficial itself.
- Binder type tools make it easier for people to actually reproduce published code due to small additional burden on top of code publication.
- How long should code be reproducible for?
- Could build in verifiability (i.e. unit tests for the research output)
- More reproduciblity focussed repositories (i.e guarantee a particular version will be available or MRAN repository that snapshots CRAN daily).

