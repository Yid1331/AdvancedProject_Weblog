# AdvancedProject Weblog 

### Stage I. Subject Confirmation  
Literature study concludes: VR helps empathy  
> ~~In past research, most of the VR scenes were the restoration of real scenes~~    

`don't do real environment` --- interactive scene (No simulation)  

VR scenes are often used for psychotherapy or vocational training  
Few applications of VR technology to eliminate cognitive differences (empathy) between men and women

`Women are sexually harassed` --- Research Event
***

### Stage II. Design Questionnaire  
Two kinds of questionnaires, one for men and one for women   

Questionnaire 1  
- Find out the time, place, and scene when women were sexually harassed  
- What types of sexual harassment are most prevalent
- Feelings of being sexually harassed
- Will it fight back, the way of counterattack?
- How to heal?

Questionnaire 2
- What do men perceive as sexual harassment?
- Why do you think women are more likely to experience sexual harassment?
- Compare the differences between the two questionnaires

[Questionnair PDF](https://github.com/Yid1331/AdvancedProject_Weblog/tree/main/Questionnaire)


***

### Stage III. Analysis Questionnaire

<img src="https://user-images.githubusercontent.com/81423727/203316138-773ebbd4-8efa-440f-85e6-efb44aecda5a.png" width="50%" height="50%">

<img src="https://user-images.githubusercontent.com/81423727/203317913-b7657dec-51f9-4b3a-8f97-3616b4feb93d.png" width="50%" height="50%">

**Questionnaire extraction design elements**

Time and Place: `dusk or evening`  `outdoors`

Difference 1:   
> Survey shows that most men don't think looking girls up and down is considered sexual harassment; but the girls think it's sexual harassment.

Difference 2:   
> Most men think that girls have the ability to fight back against sexual harassment???

Tips:   
> Women feel that seeking comfort from someone they trust can heal from sexual harassment

The overall atmosphere is finalized：
> loneliness, horror, barrenness, desolation
> Main color tone: Red, Orange, Gray...

***

### Stage IV. Design Point Refinement

**Environment**
> Surroundings: 18:00-24:00 (evening - night - early morning ===>Dynamic Weather System)
> 
> Enviroment: Outdoor?? Public transport???
> 
> Ambient sound: Vulgar language, indecent gestures, harassing phone calls...
> 
> ~~Everything is bigger than normal, especially the presence of NPCs (props)~~  
> 
> ~~Roadside elements: naked male billboards sexually suggestive statements, random flirtatious passers-by in the distance~~

#### ~~Event 1     City Scene~~  
> ~~Harassing phone calls appear over time, family members urge home calls, there will always be some billboards~~

#### Event 2    Outdoor  
`Encounter a threatening thing, a bunch of flies, just leave quickly`

#### Event 3    On the road  
> Passing a single-plank bridge, a very narrow alley,   
> there are ~~moss~~ on the wall (disgusting things), touching it will cause `the handle to vibrate`

#### Event 4   Interaction
> Look up and down==> searchlights  
> Make a sound, there will be more spotlights  
> Fear of being watched: spotlights, the eyes and evaluations of people around

***

### Stage V. Modeling

Use Blender to model the scene and props   
Export mesh, material, animation... to Unreal Engine

> <img src="https://user-images.githubusercontent.com/81423727/203324765-57798cad-ed38-4f53-a74b-6ad492218a5a.png" width="50%" height="50%">

### Stage VI. Interaction Function Realization

**Dynamic Weather System**

Weather changes over time to produce dusk, night, morning

> <img src="https://user-images.githubusercontent.com/81423727/203325258-6e9b5714-bfbb-48ea-9d84-9bfb120d17b2.png" width="50%" height="50%">

**Light System**

> <img src="https://user-images.githubusercontent.com/81423727/203325867-aaa9a795-1ee2-4c93-b265-bfb0ab7ce15b.png" width="50%" height="50%">

**Character Smooth Locomotion**

> <img src="https://user-images.githubusercontent.com/81423727/203326216-9a29dbba-8dbd-40ff-abb1-987c53c380f8.png" width="50%" height="50%">

**Interaction-Trigger System**

Grab Stone
> <img src="https://user-images.githubusercontent.com/81423727/203326830-1c1e2505-d850-4ce5-a2ec-a39ba9851bd0.png" width="50%" height="50%">

Haptic System
> <img src="https://user-images.githubusercontent.com/81423727/203327275-a1195698-81b0-4550-8406-436c98ad32dd.png" width="50%" height="50%">

Searchlight
> <img src="https://user-images.githubusercontent.com/81423727/203327474-36c4f87a-4059-47ed-98e8-215e0ea92cc3.png" width="50%" height="50%">

Bonfire
> <img src="https://user-images.githubusercontent.com/81423727/203328428-1f873200-9802-4648-b47d-f960931ae2f0.png" width="50%" height="50%">

Snow
> <img src="https://user-images.githubusercontent.com/81423727/203328650-dae850c9-7fb5-46bc-85fb-9ac28d7f7f9a.png" width="50%" height="50%">

### 6. Test
