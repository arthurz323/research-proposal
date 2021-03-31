Title: Visually-guided behaviour... visuomotor circuit...
========

Lay Summary (max. 200 words)
----------------------------



Scientific Summary (max. 200 words)
-----------------------------------




Background (max. 700 words)
---------------------------

Primates heavily rely on forelimbs to interact with the external environment. Forelimb reaching behaviour necessitates complex visuomotor cortical computations of visual stimulus perception and interpretation, target location, action preparation, selection, and execution [1,2]. Upon visual presence of the target, motor planning information from the higher-level cortical areas has to converge with the lower-level visual information to initiate a successful reach. Such process and its underlying neural mechanisms have been extensively studied in human and non-human primate models [2-5], and immense evidence has pointed out that the posterior parietal cortex (PPC), a key hub that conducts sensorimotor transformation, is necessary for the successful performance of visually-guided reaching [2,6-14].

However, the PPC alone does not paint the whole picture; to depict the neural (sub)circuits controlling the visually-guided reaching behaviour and further dissect the role of each node and their interactions, recent visuomotor experiments are shifting towards using mouse models [1,15-20]. Apart from the availability of the latest viral, genetic, electrophysiological, and projection-specific inhibitory tools that allow neuronal-resolution experimental manipulations and circuit mapping, comprehensive knowledge about the mouse brain and its reduced complexity will also aid teasing out basic visuomotor neural mechanisms [1]. Moreover, homologous with which in primates, forelimb reaching behaviour is too highly prevalent in rodents [1,19,21,22]. Therefore, advancing visuomotor processing research on rodents is essential for ethological and translational visuomotor neural circuits mapping.

Indeed, experimental work on mouse models has been fruitful; the role of PPC and the visuomotor (sub)circuits it belongs to are revealing. The PPC not only has recurrent anatomical connections with visual cortices, especially the primary visual cortex (V1), and the secondary motor cortex (M2) [20,23-26], these projections are found to be functionally necessary for visuomotor transformation and integration [17,20,24,27]. Specifically, visual information encoded by the V1 goes to the PPC [24], the PPC-M2 neurons use which to selectively control movement planning, selection, and its kinematic features (i.e., "geometry of motion") [20,26], and the M2 combining with its adjacent anterior cingulate cortex (ACC) in turn provide movement-related visual predictive flow back to the V1 [27]. Together, these areas complete the visuomotor processing loop that potentially controls the visually-guided reaching behaviour.

One caveat communal to above-mentioned studies is that the behavioural task (joystick/lever push based on visual discrimination [17,20,24]) itself is not, arguably, initiated from direct visuomotor-coupling like visually-guided reaching behaviour; but rather, visual and motor processes in the task are separately coupled with higher-level cognitive processes. Additionally, licking as motor output has limited translational value [1]. Therefore, adapting the "golden-standard" visually-guided reaching behavioural paradigm in primates to rodents is indispensable. Galiñanes et al (2018) took the initiative to make such adaptation, reach for water droplets, on head-fixed mice has been confirm by our currently on-going experiment to be quickly learnable, clearly trackable, easily implementable and modifiable.

Despite the prominent progress in disentangling visuomotor processing from all aspects of the experimental work, several questions and limitations remain to be addressed. Existing visuomotor circuit maps are under two-node scale, no study has extended a two-node connection to a closed visuomotor circuit loop; how visual information integrates into the motor system resides in a speculative level. Particularly, the ACC and M2 both project to the V1. Although the ACC-V1 projection has been studied [25,28,29], the V1's contribution to the PPC-M2 visual-information-integrated, motor-specific projection, and the feedforward the V1 receives from the M2, i.e., how the connections among V1, PPC, and M2 are formed and changed over behaviour, are poorly understood. Given difference among behavioural paradigms, visually-guided reaching behaviour that directly recruits visuomotor processing has not been systematically studied in rodents, let alone the neural (sub)circuit controls it, and the behaviour paradigm from Galiñanes et al. (2018) does not contain a salient visual cue that guides the reach. More importantly, the physiological connectivity among each visuomotor circuit node is unknown. Therefore, this study offers to tackle issues by further developing the visually-guided reaching behavioural paradigm, expanding two-node mono-directional visuomotor cortical projection mapping into a closed three-node visuomotor circuit loop, and dissecting the physiological function of each node with high-density electrophysiology probes [30] and terminal excitatory and inhibitory optogenetics.



Proposed Research (main part; max. 1400 words)
----------------------------------------------

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

aim 1: novel behavioural paradigm development

aim 2: in naive mice, map physiological information V1-PPC, & M2-V1

aim 3: dissect physiological & temporally role of each node by axonal terminal inhibitory opto


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

---
current project working on circuit mapping PPC-pM2:

- naive mice, visuomotor

- expert mice, 

---


### discussed with Matt:

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



