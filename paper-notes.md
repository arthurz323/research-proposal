# Hwang et al., 2019 "corticostriatal flow of action selection bias"



## Question

- PPC (posterior parietal cortex) contributes to decision making & movement control, but which input & output pathways support these functions?



## Parallel Circuits

### PPC-STR (dorsal striatum)

- receives stronger input from association areas (**??**)
    
- encodes *history-denpendent choice bias*:
    - inhibit PPC-STR neuron decreases history-denpendent choice bias

- **select action**

### PPC-pM2 (posterior secondary motor cortex)

- receives stronger sensorimotor input:
    - inhibit PPC-pM2 neuron alters movement kinematics

- **control movement**



## Techniques & Results

### PPC-STR & PPC-pM2 Represent Largely Distinct Subpopulations

- inhibit PPC-STR soma during ITI (inter-trial interval), but not choice period, *weakens* history-denpendent bias of the following trial
    
    ➡️  PPC encodes history-dependent bias during **ITI**, and used by downstream STR during choice
    
➡️  need to identify flow of bias

**Projection tracing:**

- unilateral anterograde AAV-CAG-tdTomato in PPC,  ➡️  PPC projects <sup>1</sup> to:
    - **pM2**
    - **STR**
    - S1 (primary somatosensory cortex)
    - associative thalamus
    - auditory cortex
    - visual cortex
    - superior colliculus

> <sup>1</sup> projections are largely *ipsilateral* to the injection site.

- unilateral RVDG-GFP (retrograde glycoprotein-deleted rabies virus encoding GFP) in STR to PPC & RVDG-tdTomato in pM2 to PPC in the same animal <sup>2</sup>

- unilateral retrograde CTB (cholera toxin subunit b)-red in STR to PPC & retrograde CTB-green in pM2 to PPC in the same animal <sup>2</sup>

> <sup>2</sup> The contralateral PPC contained only 2% ± 1% of all retrogradely labeled PPC neurons from STR injections & 4% ± 1% from pM2 injections, thus only *ipsilateral* is analysed.


**Identify spatial distribution of PPC-STR & PPC-pM2 neurons:**

- PPC-STR is more than PPC-pM2

- PPC-STR & PPC-pM2 are largely overlapped *spatially*, yet *PPC-pM2 is more superficial, lateral, and posterior*

- only less than 10% PPC neurons are double-labelled  ➡️  PPC-STR & PPC-pM2 represent largely distinct PPC neuron subpoplations


### PPC-STR & PPC-pM2 Neurons Receive Distinct Long-Range Inputs

- CAV-Cre in STR/pM2, & a mixture of helper viruses in unilateral PPC  ➡️  restrict viruses expression to PPC-STR/pM2 starter neurons

- three weeks later, inject EnvA-RVDG-eGFP in PPC  ➡️  only infect starter neurons; trans-complementation allows it to trans-synaptically infect pre-synaptic neurons

- inputs to PPC are mainly *ipsilateral*<sup>3</sup>, PPC-STR & PPC-pM2 have sig. different input from:
    - M1 (PPC-pM2 > PPC-STR)
    - upper-body S1 (PPC-pM2 > PPC-STR)
    - cingulate areas (PPC-STR > PPC-pM2)
    
> <sup>3</sup> visual cortex gives **biggest** input chunk (>20%) to both PPC-STR & PPC-pM2

➡️  PPC-pM2 neurons receive more sensorimotor inputs, PPC-STR neurons receives more association inputs.


### PPC-STR Neurons encode History-Dependent Action Bias

PPC-STR & PPC-pM2 form parallel subsystems with distinct functions  ➡️  does any of these subsystem deal with history-dependent action bias?

- decision making task: press the joystick in the same direction as the visual stimulus (forward or downward drifting gratings) following the auditory cue

- full logistic regression model (equation 1): the probability of choice on a given trial is a function of the current trial stimulus, choice-outcome history, and a constant bias.

    ![equation 1](https://github.com/arthurz323/research-proposal/blob/master/pics/equation1.png)

    - the probability of choice significant dependent on choice-outcome history in the two-choice joystick task

    - estimate the continuously varying history-dependent bias on a trial-by-trial basis, which is a variable internal to the mouse and not directly measurable (equation 3)


![equation 3](https://github.com/arthurz323/research-proposal/blob/master/pics/equation3.png)
    - 

![euqation 6](https://github.com/arthurz323/research-proposal/blob/master/pics/equation6.png)


### PPC-STR Pathway Is Required for History Bias





- two-photon calcium imaging during decision-making

- inhibitory opto

    - PPC-STR neuron soma or terminal
    
    - PPC-pM2 soma



