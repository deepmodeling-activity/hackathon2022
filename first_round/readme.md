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
- Using dflow with to submit job on cluter
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

### Proposal 
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
   
You can find the template for proposal writing in the [supporting file](https://github.com/deepmodeling-activity/hackathon2022/blob/main/supporting/proposal_writing_template.md). 

You should submit your proposal by email to **hackathon@dp.tech** with the email title, ***yourName_WechatID_proposal***.

1. We invited three people to share their dflow workflows. [Link](https://github.com/deepmodeling-activity/hackathon2022)

## Stage 3: hack your future, run the world
1. You will receive the feedback about your proposal on 07/25/2022 18:00 (GMT+8). You can check the information [here](https://github.com/deepmodeling-activity/hackathon2022)

2. When you started to fulfill your potential to complete your project, we are here to provide you with several helpful tutorials and lectures for your reference. You can check the information [here](https://github.com/deepmodeling-activity/hackathon2022)

3. The ***deadline*** to submit your project is on 08/04/2022 23:59 (GMT+8). You are supposed to submit it by email to hackathon@dp.tech.

And then, mentors will review your projects to determine whether you can enter the final round. The project presentation is on **08/06/2022 09:00 (GMT+8)**. 


