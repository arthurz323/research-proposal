Title: Visually-guided behaviour... visuomotor circuit...
========

Lay Summary (max. 200 words)
----------------------------



Scientific Summary (max. 200 words)
-----------------------------------




Background (max. 700 words)
---------------------------

Primates heavily rely on forelimbs to interact with the external environment. Forelimb reaching behaviour necessitates complex sensorimotor cortical computations of sensory stimulus perception and interpretation, target location, action preparation, selection, and execution <sup>1,2</sup>. Such behaviour and its neural mechanisms have been extensively studied in non-human primate models <sup>3,4,5,6</sup>, yet still little is known about sensorimotor information cortical integration. To map out the underlying sensorimotor neural (sub)circuit and further dissect the role of each node and their interaction, it is essential to develop sensorimotor behavioural paradigm in mouse models so that the latest genetic and electrophysiological tools can be implemented.

Existing studies which use forelimb reaching task ... lack... & inclusion of multiple sensory modalities & ...factors ... hinders the decomposition. ... based on work from Galinanes 2018, this project further adjust the directional reaching paradigm, ... pure visuomotor, clearly trackable behaviour, easily adaptable/modifiable difficulty...

after behaviour development, cortical circuit:

As forelimb reaching behaviour in rodents highly resemble primates,

recently has it been adapted into mouse models to exploit genetic and electrophysiology tools <sup>1,</sup>.



 smoothly and consistently, sensory and motor information need to be highly coordinated. 

- visuomotor behaviour
    
    - forellimb reaching is frequent yet needs complex cortical computation
    
    - extensively studied in primate models, carefully tease out each node of the neural circuit --> use mouse models
    
        - advantages compare to primate:
        
    - "the close resemblance of the reach-to-grasp sequence supports the hypothesis that reaching behavior is homologous in rodents and primates (Sacrey et al., 2009; Whishaw et al., 1992)" Galinanes et al., 2018

- three-node loop

    - V1: primary/basic computation
    
    - PPC: viusally-guided reaching & visuomotor coupling
    
    - pM2: esp. introduce PPC-pM2 functioning from Hwang et al., 2019

    - pM2 projects back to V1

- behaviour paradigm

    - water restriction
    
    - viusally-guided reaching behaviour
    
    - head-fixed (allow multi-probe recording & opto; avoid freely moving period cuz some mice never learnt to use the forellimb, when they cannot reach the spout with tongue they give up; all mice in HF box use forellimb to get water from the very beginning; tho limitation is that FM mice learn faster, get more reward, performance more stable, more "natural" behaviour, less stress)
    
    - stick with current behaviour, but add one more spout  ➡️  left, mid, right
    
        - instead of moving all the way to 7mm, distance stays in a comfortable region (depends on the body size of each mouse), difficulty of the task is demonstrated by the pattern of lighting-up:
        
        1. single spout: build light-water association till >75%
        
            - left only
        
            - mid only
        
            - right only
        
        2. spout lights up: left  ➡️  mid  ➡️  right
        
            - pattern became predictable
        
            - ITI gradually  ⬇️ to max. no. of trial & success rate for expert mice
        
        3. introduce mis-match: right  ➡️  mid  ➡️  left
        
        4. move-on to recording when >75%
        
    - use infrared beam to detect movement trajectory & allow cortical inactivation at a specific behavioural point


    
- cortical activity manipulation

    - terminal inhibitory opto (Komiyama 2019)





Movement is guided by vision.

Vision, as a dominant sensation, extensively contributes to behaviour (check motivation letter & neural dynamics proposal). One key hub of the visuomotor information coupling is posterior pariatal cortex (PPC), evidence has been found in both primates and mice (ref. here). Specifically, PPC lesion in human causes optic ataxia (OA), i.e., inability to guide the hand to viusal targets, without pure motor/visual deficit; in mice, bilateral PPC-pM2 neurons inactivation disrupts the preparation of movements to produce fast & consistent movements...

evidence has shown that PPC receives projections from V1 (V1 feeds info to higher-level cortex e.g., PPC; find refs!), pM2 projects to V1 with motor-coupled visual flow predictions, yet in this visuomotor cortical circuit, the physiological information sent & received by V1 in unknown, let alone how these information change over sensorimotor behaviour learning.

current project working on circuit mapping PPC-pM2:

- naive mice, visuomotor

- expert mice, 

thus, this project aims to expand the current two-node mono-directional visuomotor cortical projection into a three-node visual-processing-centred visuomotor cortical circuit, 


Proposed Research (main part; max. 1400 words)
----------------------------------------------

aim 1: novel behavioural paradigm development

aim 2: in naive mice, map physiological information V1-PPC, & M2-V1

aim 3: dissect physiological & temporally role of each node by axonal terminal inhibitory opto

### Objectives

- why this is important

- **hypotheses???**: V1 plays a vital role (is essential) in sensorimotor cortical circuit during visually-guided behaviour

1. V1 performs low-level visual processing and provides PPC with basic motor-related visual information for further visuomotor integration
    
    - exp: V1-PPC axonal terminal inactivation
    
2. M2 provides predictive motor-related visual flow to V1 that is essential for visuomotor learning

3. V1-PPC-M2-V1 subnetwork becomes increasingly coordinated across learning of a visuomotor task

    - i should hypothesise about the property/characteristics of the physiological info, e.g., pM2 sends predictive flow (corollary discharge) to V1, and V1 performs on-site computation (filtration? coupling?), and send motor related flow to PPC (ask Matt...)
    

PPC-pM2 circuit mapping, i.e., **V1-PPC-pM2-V1** *ipsilateral*

[visual cortex gives **biggest** input chunk (>20%) to both PPC-STR & PPC-pM2

➡️  PPC-pM2 neurons receive more sensorimotor inputs, PPC-STR neurons receives more association inputs.] Hwang 2019

➡️  sensorimotor cortical circuit mapping, / sensorimotor predictive coding mapping:

- ACC is bidirectionally connected with pM2

- ACC gives predictive signals to V1

- also primary visual input (from eyes) goes to V1, V1 does "basic (?)" computation,

- sends "processed" motor-info-coupled visual info to PPC

- M2 sends a predictive flow to V1

- thus completes the update loop

[the input from ACC to V1 has a role in attentional modulation of visual responses (Zhang et al., 2014) and experience-dependent spatial predictions (Fiser et al., 2016).] Leinweber 2017




### Research Plan

discussed with Matt:

- do V1-PPC-pM2

- question: what info, i.e., physiologically speaking, does V1-PPC & pM2-V1, i.e., how does V1 involve/contribute to visuomotor behaviour, & how does this "loop" update over learning

- techniques:

    - npx*3, with V1 & PPC back-to-back together
    
    - terminal inhibitory opto, in pM2-V1 terminal, & V1-PPC terminal
    
- behaviour:

    - my new behaviour :)
    
- note: Leinweber 2017 uses Ca imaging, i.e., not physiological, thus my stuff will be novel :)


- timescales (Gantt chart)

    - **coincidence detector**: express ChR2 to PPC-M2 projections -> stimulate these axons in M2 during behaviour & npx recording -> electrical signal will back-propagates to somas in PPC:
    
        - light on: AP from PPC-M2 projecting neurons will be cancelled by ChR2 stimulation -> correspond npx channels will loss AP signal
        
        - light off: AP from PPC-M2 projecting neurons will successfully reach M2 -> npx picks up AP signal;
        
        - compare light on & off conditions -> accurately identify channels in npx that pick up AP signals from PPC-M2 projecting neurons
        
    - the same behaviour? a year of new behaviour development
    
    - expand the current circuit, & use different techniques to acquire info from all levels (e.g., inhibitory opto, meso scope imaging, more npx probes)
    
    - decoding success rate?
        
        - layer/ area specific decoding
    
    - for research plan:
    
        - behaviour & analysis sandwiched to allow adaptation
    
        - less well for a short time rather than everything perfect for a long time
    
    - handedness change may be caused by the uncomfortable behavioural setting (under head fixed condition), need to check lateralised studies in rodents
    
    - introduce double-step hand movement to mice??
    
    - **CAUTION! do NOT plan too much! EVERYTHING takes a lot of time!! V1-PPC-M2/ACC needs two postdoc (2-year)**

- contingency plan


References
----------

1. Galiñanes, Gregorio Luis, et al. “Directional Reaching for Water as a Cortex-Dependent Behavioral Framework for Mice.” *Cell Reports (Cambridge)*, vol. 22, no. 10, 2018, pp. 2767–2783.

2. Archambault, P.S, et al. “Visually-Guided Correction of Hand Reaching Movements: The Neurophysiological Bases in the Cerebral Cortex.” *Vision Research (Oxford)*, vol. 110, no. Pt B, 2015, pp. 244–256.

3. Mountcastle, V. B, et al. “Posterior Parietal Association Cortex of the Monkey: Command Functions for Operations within Extrapersonal Space.” *Journal of Neurophysiology*, vol. 38, no. 4, 1975, pp. 871–908.

4. Georgopoulos, AP, et al. “On the Relations between the Direction of Two-Dimensional Arm Movements and Cell Discharge in Primate Motor Cortex.” *The Journal of Neuroscience*, vol. 2, no. 11, 1982, pp. 1527–1537.

5. Schwartz, AB, et al. “Primate Motor Cortex and Free Arm Movements to Visual Targets in Three- Dimensional Space. I. Relations between Single Cell Discharge and Direction of Movement.” *The Journal of Neuroscience*, vol. 8, no. 8, 1988, pp. 2913–2927.

6. Apostolos P. Georgopoulos, et al. “Neuronal Population Coding of Movement Direction.” *Science* (American Association for the Advancement of Science), vol. 233, no. 4771, 1986, pp. 1416–1419.

Hwang, Eun Jung, et al. “Corticostriatal Flow of Action Selection Bias.” *Neuron (Cambridge, Mass.)*, vol. 104, no. 6, 2019, pp. 1126–1140.e6.

Jun, James J, et al. “Fully Integrated Silicon Probes for High-Density Recording of Neural Activity.” *Nature (London)*, vol. 551, no. 7679, 2017, pp. 232–236.

Schwarz, Cornelius, et al. “The Head-Fixed Behaving Rat-Procedures and Pitfalls.” *Somatosensory & Motor Research*, vol. 27, no. 4, 2010, pp. 131–148.

Guo, Jian-Zhong, et al. “Cortex Commands the Performance of Skilled Movement.” *ELife*, vol. 4, 2015, p. e10774.


