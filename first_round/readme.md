## Introduction 
What's up hacker! Glad that you accepted the challenge! 
There are three stages in the first round. These stages are intended to guide you from not knowing dflow to a master of using dflow. 

## Stage 1: prepare your senses, learn to flow
### Dflow Tutorials
We prepared a series of tutorials to learn dflow. You can find it here: [dflow-tutorials](https://github.com/deepmodeling/dflow/tree/master/tutorials)

There are several topics we intend to cover in this series:
- Installation and setup 
- Using dflow to write a simple workflow 
    - [dflow-helloworld.ipynb](https://github.com/deepmodeling/dflow/blob/master/tutorials/dflow-helloworld.ipynb)
    - [dflow-python.ipynb](https://github.com/deepmodeling/dflow/blob/master/tutorials/dflow-python.ipynb)
- Using dflow with to submit job on cluster
    - [dflow-slurm.ipynb](https://github.com/deepmodeling/dflow/blob/master/tutorials/dflow-slurm.ipynb)
- Advanced functionality of dflow
    - running jobs in parallel: [dflow-slices.ipynb](https://github.com/deepmodeling/dflow/blob/master/tutorials/dflow-slices.ipynb)
    - writing while loop in dflow: [dflow-recurse.ipynb](https://github.com/deepmodeling/dflow/blob/master/tutorials/dflow-recurse.ipynb)
    - reusing operated nodes: [dflow-reuse.ipynb](https://github.com/deepmodeling/dflow/blob/master/tutorials/dflow-reuse.ipynb)
    - complex condition: [dflow-conditional.ipynb](https://github.com/deepmodeling/dflow/blob/master/tutorials/dflow-conditional.ipynb)
### Dflow Tutorials Lecture
You can go through the tutorials at your own pace. But you can also watch the lecture here: [VooV Meeting](https://voovmeeting.com/dm/DuRPJs8AhN37) ([Schedule](https://github.com/deepmodeling-activity/hackathon2022#stage-1-prepare-your-senses-learn-to-flow))

**If you have questions, we suggest you raise an issue in [dflow issues](https://github.com/deepmodeling/dflow/issues).**


## Stage 2: create your goal, explore the world 
In this stage, you are expected to propose your own project. The goal is to solve the repetitive task using dflow. For instance, we can use dflow to automate the file preparation and the results post-processing in doing Density Functional Theory (DFT) calculation. You can check out an example using VASP as the DFT calculator here: [How to run VASP with dflow](https://zhuanlan.zhihu.com/p/540665677).

<p align="center"><strong>Start brainstorming!</strong></p>

### About proposal 

#### Topics 
For starters, you need to choose one of the six topics in this competition.
- AI-assisted molecular dynamics simulations: [DeePMD-kit](https://github.com/deepmodeling/deepmd-kit), [DPGEN](https://github.com/deepmodeling/dpgen)
   - Participants in this track should propose a project that is on AI assisted molecular dynamics simulation and tries to improve the level of automation in training data generation algorithm under concurrent learning framework.
- AI-assisted electronic structure calculations: [DeePKS-kit](https://github.com/deepmodeling/deepks-kit), [ABACUS](https://github.com/deepmodeling/abacus-develop)
   - Participants in this track should propose a project that is on first principle calculation and/or machine learning functional. Some examples are: 
        - Try to improve the tedious file preparation and post-processing of results using first principles calculation software (quantum chemistry, DFT).
        - Try to improve the level of automation in concurrent learning when using DeePKS-kit.
- Differentiable force field calculation engine: [DMFF](https://github.com/deepmodeling/DMFF)
   - Participants in this track should propose a project that is on differentiable force file calculation. The project should try to improve the difficult parameter optimization process and enhance the low level of automation in force field development (including but not limited to classical force field, polarizable force field etc.). 
- Partial differentiable equation numerical solution algorithm library: [FEALPy](https://github.com/deepmodeling/fealpy)
    - Participants in this track should propose a project that solves the problem of optimal parameter selection in numerical calculation with parametric values
- Computational fluid dynamics suite for reacting flow with machine learning: [DeepFlame](https://github.com/deepmodeling/deepflame-dev)
   - Participants in this track should propose project that uses DeepFlame to solve problems in flamelet combustion calculation using tabulated chemistry method. Problems include but not limited to cumbersome workflow, difficult parameter optimization, slow generation of high-dimensional databases, and low level of automation coupling with CFD. 
- Workflow development kit: [dflow](https://github.com/deepmodeling/dflow/)
    - Participants in this track should work on issue proposed by dflow developer. Please see this [issue](https://github.com/deepmodeling/dflow/issues/34)
   
#### Template
You can find the template for proposal writing in the [supporting file](https://github.com/deepmodeling-activity/hackathon2022/blob/main/supporting/proposal_writing_template.md). 

#### Submission
- Deadline: 07/24/2022 18:00 (GMT+8). After this time, your proposal will not be reviewed.
- File format: PDF is preferred.
- File name: yourName_WechatID_proposal.pdf
- Please send your proposal to hackathon@dp.tech with email title, yourName_WechatID_proposal 

### About ideas
We invited three guests to share their dflow workflows. If you do not know where to start for the proposal, come and check it out. [Schedule](https://github.com/deepmodeling-activity/hackathon2022#stage-2-create-your-goal-explore-the-world)


## Stage 3: hack your future, run the world

### Proposal Feedback
You will receive the feedback of your proposal by 07/25/2022 18:00 (GMT+8). It will return to you via email. 

### Dflow Night School
We invited some guests to give helpful tutorials and lectures for your reference. This series will dive deep on the code, so it will help you when you are working on your own project. [Schedule](https://github.com/deepmodeling-activity/hackathon2022#stage-3-hack-your-future-run-the-world)

### Final Project Submission 
- Deadline: 08/04/2022 23:59 (GMT+8). 
- File format: please compress your code, data and other necessary files together.
- File name: yourName_WechatID_project.zip
- Please send your final project to hackathon@dp.tech with email title, yourName_WechatID_project

#### Grading 
Total points: 100pts.

Mentors of each topic will grade your work from three aspects: 
- Degree of completion (40%): the final project will be compared with the proposal. Mentors will evaluate on what you proposed and what you have achieved.
- Degree of automation (40%): you are supposed to explain the traditional workflow in your documentation. Mentors will evaluate your final project base on the degree of automation compared to the traditional workflow.
- Documention completeness (20%): you are responsible for your own project, which means you should write the documentation of your code carefully. Mentors will grade on the effort on reading and using your code.

- **BONUS: presentation** (10pts): presentation will be bonus points for your project. Key points to cover in the final presentation: traditional workflow and what are the problems, your workflow and what are the advantages.

**NOTE: we should be able to use and read your code! This is important for the grading process!**


