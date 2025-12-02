# Table of Contents
1. [CardioCoLab: Collaborative Learning of Embryonic Heart Anatomy in Mixed Reality](#CardioCoLab)
2. [Volume Rendering for Retinal Surgery](#Retinal)
3. [Distance Visualizations for Vascular Structures in Desktop and VR](#Distance)
4. [An interaction metaphor for enhanced VR-based volume segmentation](#interaction)
5. [Learning Hand Anatomy with Sense of Embodiment](#Learning)
6. [An Endoscope Interface for Immersive Virtual Reality](#Endoscope)
7. [Virtual reality platform for training and planning implantations of occluder devices in left atrial appendages](#Virtual)
8. [Learning Anatomy through Shared Virtual Reality](#LearningAnatomy)


# Relevant Papers

## <font color="red">EXTRA RELEVANT</font> CardioCoLab: Collaborative Learning of Embryonic Heart Anatomy in Mixed Reality [PAPER](./EmbryoHeart.pdf) <a name="CardioCoLab"></a>

**What is special?** 
Developed a collaborative environment for multiple users to study an embrionic heart in Mixed Reality. Demonstrated that their product helps to learn (N=12).

**Details**

* Made in the past another system for VR -- "Cardiogenesis4d: interactive morphological transitions of embryonic heart development in a virtual learning environment."

* Timelapse of development stages over time. 

* Used MudBun (https://longbunnylabs.com/mudbun/) for procedural volumentric mesh generation [in Unity]. 

* Focus on collaborative learning with a moderator (a teacher) who leads a seminar session.

* A tool to visualise the heart, reposition, rotate, and deform through hand interactions (but then then say there're only controller interactions?? because of issues with tracking). Also, playes animations.

* Users can also change the colour of different structures. Users can also trigger displaying of annotations. 

**Study**

* Both medical students and teachers with experience evaluated the system.

* Questionnaires: 
    - SUS for usability
    - ARI [AR Immersion] for immersion
    - TAM to assess Perceived Usefulness (PU) and Perceived Ease of Use (PEU)
    - GEQ Game Experience Questionnaire 
    - Post Study Interview

* Only use the mean and standard deviation

* Summarised open-ended qualitative feedback in the end

---

## Volume Rendering for Retinal Surgery [PAPER](./VolumeRenderingRetinalSurgery.pdf) <a name="Retinal"></a>

**What is special?** 
Introduced a visualisation technique for retinal microsurgery from the intraoperative OCT (optical coherence tomography). As a sergeon manipulates the surface, they create a visualisation of retina and the instrument.

**Details**

* Better assessment of needle penetration depth via a special projection (Layer-Adjusted Maximum Intensity Projection)

* Introduced colour maps

* Designed a new volume rendering method based on ray casting

---

## Distance Visualizations for Vascular Structures in Desktop and VR [PAPER](./VascularStructuresVR.pdf) <a name="Distance"></a>

**What is special?** 
Summarised visualisation techniques (13 in total) for surface rendering of 3D vessel surfaces. Provide implementations of those techniques in Unity. Wanted to promote further research in this area.

**Details**

* Described what aspects of human vision and perception are important to consider

* Described the techniques

---

## An interaction metaphor for enhanced VR-based volume segmentation [PAPER](./ManualSegmentationVR.pdf) <a name="interaction"></a>

*Segmentation:* process of taking a 2D or 3D image of body and then 'segmenting' it into different meaningful regions (e.g., organs, bones, vessels, fat, etc.).

**What is special?** 
Introduced an interaction metaphor to do segmentation of medical images in VR. Conducted a user study (N=8).

**Details**

* Explained the interaction tool, the *wedge tool*, that consists of three planes, and described what it could do

* Described how to interact with it to trigger certain events (e.g., toggle medical data, change positions of the planes, etc.)

**Study**

* Evaluated framerates

* User study in two parts:
    - Basically tought how to use the tool in four tasks
        - collected time data for three tasks and set a time limit for the fourth task.
    - Editing the medical model with the tool
        - collected time data for three tasks and set a time limit for the fourth task.

* Used a custom questionnaire with eight questions

---

## <font color="red">EXTRA RELEVANT</font> Learning Hand Anatomy with Sense of Embodiment [PAPER](./HandAnatomyVR.pdf) <a name="Learning"></a>

**What is special?** 
Implemented a VR prototype for learning hand anatomy, where the user looks at their hands, sees them in motion and the system renders the anatomical structure of the hand accordingly. Tested with users with no medical background (N=7).

**Details**

* A domain expert set requirements for the prototype for it to adhere the anatomy curriculum 

* Determined the vertext budget for Oculus Quest at 200K vertices (not important, just interesting)

* Retopologised their initial model of whooping 817K to 97K vertices

* Used Blender for skeletal animations

* Can toggle the preview of different anatomical structures on demand (e.g., show/hide bones, muscles, nerves, etc.)

* Used Unity

**Study**

* Questionnaires: 
    - SUS for usability
    - IPQ Igroup Presence Questionnaire for Presence
    - Sense of EMbodiement (Gonzalez-Franco and Peck)

---

## <font color="red">EXTRA RELEVANT</font> An Endoscope Interface for Immersive Virtual Reality [PAPER](./EndoscopeInterfaceVR.pdf) <a name="Endoscope"></a>

**What is special?** 
Created a new endoscopic interface for HTC Vive. The controller was adapted to mimic an endoscope. Actually is pretty similar in the spirit to what we wanted to do with our simulator -- affordable environment that can be easily deployed in hospitals for training. 

**Details**

* Attached Microsoft Surface Dial to a controller to emulate the endoscope

* Created a mesh of the endoscope and rigged it to a special skeleton to have more control

* Simulation of the endoscope movement (only forwards and backwards) was realised by creating a special wooden mount that constrained a rod which had a vive tracker attached

* Didn't have the user study but simply mentioned there were designing it

--- 

## Virtual reality platform for training and planning implantations of occluder devices in left atrial appendages [PAPER](./AtrialAppendagedVRPlatform.pdf) <a name="Virtual"></a>
 
**What is special?**
Introduced a VR platform for patient-specific cardiac geometry inspection. Tested with clinical experts and researchers (N=5).

**Details**

* They segmented geometry from CT scans, then used Marching Cubes to create a surface mesh

* Users can move, rotate, zoom in/out and slice geometry

* Used 2D panels to visualise extra data

* Users can implant an occluder device in the simulation (in a locked controller mode and freely moving controller mode)

* User can also move catheter and possibly insert it. Not sure

**Study**

* Apparently custom questionnaire with max score 5.0
    - platform as a training tool
    - VR as a source of motivation 
    - VR versus non-VR platforms
    - pre-operative planning tool
    -  participating in future planning session
    - added value to deﬁne device settings
    - added value to minimize mistakes during surgery
    - also some other quiestions about the ease of use


---

## <font color="red">EXTRA RELEVANT</font> Learning Anatomy through Shared Virtual Reality [PAPER](./AnatomyThroughSharedVR.pdf) <a name="LearningAnatomy"></a>

**What is special?**
An app where students get tasks to put different organs together and then can check their performance. Supports a multiplayer mode to play together and under the supervision of a professional. User study with medical students (N=2) and professors (N=4).

**Details**

* Users interconnect part of cardiac system to learn better

* Vessel models are bendable and the user can bend them (via Bezier curves)

* Emphasis on hands being variously animated to fit actions (e.g., when bending, grabbing, touching things, etc.)

* They also support Manus haptic glove

* Collaboration works in two modes: online and off-line (for all people standing in the same physical room)

* Pretty cool: each user logs with their username and password and has a personal profile assigned to them with their scores and all

**User Study**

* They had one but apparently they ended up only doing post-study interviews

---