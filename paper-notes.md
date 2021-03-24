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

    ![anatomy of circuits](https://github.com/arthurz323/research-proposal/blob/master/pics/anatomy.png)

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

PPC-STR & PPC-pM2 form parallel subsystems with distinct functions  ➡️  *Q1: does any of these subsystem deal with history-dependent action bias?*

- decision making task: press the joystick in the same direction as the visual stimulus (forward or downward drifting gratings) following the auditory cue

- full logistic regression model (equation 1): the probability of choice on a given trial is a function of the current trial stimulus, choice-outcome history, and a constant bias.

    ![equation 1](https://github.com/arthurz323/research-proposal/blob/master/pics/equation1.png)

    - the probability of choice significant dependent on choice-outcome history in the two-choice joystick task
    
    - stimulus model (equation 2): probability of the choice depends only on the stimulus & constant
    
    ![equation 2](https://github.com/arthurz323/research-proposal/blob/master/pics/equation2.png)

    - estimate the continuously varying history-dependent bias on a trial-by-trial basis, which is a variable internal to the mouse and not directly measurable (equation 3)

    ![equation 3](https://github.com/arthurz323/research-proposal/blob/master/pics/equation3.png)

To register projection neurons & compare which with *other PPC neurons*, used two-photon calcium imaging during decision-making behaviour:

- cortical excitatory neurons express GCaMP6s, 24% ± 2% of all imaged PPC neurons showed different activity for different upcoming behaviour during ITI  ➡️  these neurons reflect history-dependent bias that impacts the upcoming choice

- a weighted sum of ITI activity across PPC neurons in each trial could well reflect the history bias of that trial in the model, closely fitting the history bias that varies trial by trial.

    ![decode history bias](https://github.com/arthurz323/research-proposal/blob/master/pics/decoding-results.png)
    
➡️  A1: yes, PPC neurons output history bias info during ITI

➡️  *Q2: do PPC-STR & PPC-pM2 encode history bias differently?*

- retrograde CAV-Cre tdTomato in STR & pM2 (separately), & CaMK2-tTA::tetO-GCaMP6s & tdTomato in PPC
    
    - 47% ± 3% of all labelled PPC projection neurons showed GCaMP6 signals
    
    - PPC-STR > PPC-pM2 in number, **cortical depth**, & prevalence of tuning to the upcoming choice during ITI (N-choice tuning)
    
    - PPC-STR & PPC-pM2 have similar history-dependent bias processing & task performance
    
➡️  A2: PPC-STR neurons are more likely to tune to N-choice

➡️  *Q3:PPC-STR are deeper, does N-choice tuning increase with cortical depth?*

- correlate depth of imaging field & fraction of neurons tune to N-choice  ➡️  cortical depth ⬆️, fraction of neurons tune to N-choice ⬆️,  ➡️  **different N-choice tuning between PPC-STR & PPC-pM2 populations might be solely explained by the difference in their depths**

    - When the depths were matched, the fraction of neurons tuned to N choice in all imaged neurons in each field was not different between the two groups, yet still PPC-STR > PPC-pM2 in number.

![euqation 6](https://github.com/arthurz323/research-proposal/blob/master/pics/equation6.png)


### PPC-STR Pathway Is Required for History Bias

History bias encoding can be altered by perturbing **PPC-STR neurons**  ➡️  PPC-STR neurons soma inactivation:

- Cre-dependent halorhodopsin 3.0 bilateral injection in PPC

- wait for 8 weeks after injection for max. opsin expression

- 15% randomly selected trials during behavioural task

    - green light
    
    - 4s bilateral PPC inactivation during ITI

- **History dependence (bias) = full model accuracy (equation 1) - stimulus model accuracy (equation 2)**, i.e., the difference of choice prediction accuracy between models

➡️  history dependence sig. reduced in light-on trials  ➡️  PPC-STR neurons are essential for normal history dependency

- analogous inactivation on PPC-pM2 neurons  ➡️  history dependence does not require functional PPC-pM2 neurons soma

➡️  PPC-STR neurons are selectively involved in controlling history dependency

NOTE history dependency may mediated by downstream structure's axon bundles  ➡️  PPC-STR neurons axon terminal inactivation (in STR):

- similar results as soma inactivation

➡️  PPC-STR neurons selectively control history dependency

- **the effect size of inactivation specific to the PPC-STR neurons, both soma and terminal, is similar to what we observed when inactivate the entire PPC (by activating parvalbumin-positive inhibitory neurons)**
    
- The bias information encoded in PPC during the ITI might be offloaded to the basal ganglia where it is used to bias action selection
    
- history model: choices are predicted from choice-outcome history terms without stimulus

    ![equation 4](https://github.com/arthurz323/research-proposal/blob/master/pics/equation4.png)


### PPC-pM2 Neurons Are Involved in Movement Control

Analyse how PPC-pM2 inactivation (during ITI) affects kinematic features ("geometry of motion") of movement:

- the trajectories of movements from trial to trial was sig. reduced

    ![movement trajectories change](https://github.com/arthurz323/research-proposal/blob/master/pics/movement-trajectories.png)
    
- peak velocity of movement sig. reduced

➡️  PPC-pM2 neurons might contribute to the preparation of movements to produce faster & consistent movements

![summary](https://github.com/arthurz323/research-proposal/blob/master/pics/projection-function.png)

***PPC is involved in movement planning & online adjustment***

- PPC-pM2 activity during ITI might be used to **prime** pM2 and use which to form **preparatory activity** for a movement


---

Archambault et al., 2015 "Visually-guided correction of hand reaching movements: The neurophysiological bases in the cerebral cortex" [review in macaque]
=====================================================================================================================================

## Background

- CNS feedforward processes plan out the reaching movement, feedback is used to control for errors during movement execution & to monitor the outcome.

- Visual information has **continuous access** to motor CNS centers & make required adjustment due to changing task demands.

- PPC lesion in human causes optic ataxia (OA): inability to guide the hand to viusal targets, without pure motor/visual deficit.

    - unable to update the ongoing hand movements in **double-step target paradigm**, hand always *goes back to the original point before reaching for the next*
    
Paradigm:

- Single-step target paradigm

    - first stimulus  ➡️  first saccade  ➡️  first hand movement

- Double-step target paradigm

    - after first saccade & hand movement  ➡️  second stimulus  ➡️  second saccade  ➡️  **change in hand trajectory**
    
Quantifications:

- eye reaction time (eRT1 & eRT2): first & second saccade

- hand reaction time (hRT1 & hRT2): first & second hand reaction

- hand movement time (hMT)

- **NOTE** in double-step target paradigm, 

NOTE **double-step target paradigm** varies in location & timing of the target shift:

- new target is perpendicular/parallel to the first target

- target shift happens 0-200ms from the onset of hand movement, i.e., during hMT

- target shift happens after eRT1, i.e., during hRT  ➡️  subject usually is not conscious about the shift

    - ***add this to proposal?? use eye-tracking?? first need to figure out the viusal field of mice, i.e., can they see if the target is in front of them? also will signal-to-noise level very low???*** ALSO **track hand speed with deeplabcut??**

- online correction needs feedforward & feedback comparison, which takes place in PPC, i.e., "it is an optimal blending of cells combining feedforward & feedback signals that is crucial for the online correction of hand movements in PPC in order to contribute to online correction."
