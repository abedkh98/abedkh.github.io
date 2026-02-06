<!-- To set up your GitHub personal website:
1. Create a new repository on GitHub named <yourusername>.github.io (e.g., abedkhorasani.github.io).
2. Enable GitHub Pages in the repository settings (under Pages, select main branch).
3. Upload the following files to the repository root.
4. The website will be live at https://<yourusername>.github.io.
5. (Optional) Upload CV_Khorasani.pdf to the root for the CV download link to work.
6. Customize further as needed. This is a simple static HTML site without Jekyll for ease. -->

<!-- File: index.html (About page) -->
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Abed Khorasani - About</title>
    <style>
        body { font-family: Arial, sans-serif; margin: 20px; line-height: 1.6; }
        nav { background: #f0f0f0; padding: 10px; margin-bottom: 20px; }
        nav a { margin-right: 20px; text-decoration: none; color: #333; }
        nav a:hover { text-decoration: underline; }
        h1, h2 { color: #333; }
        ul { list-style-type: disc; padding-left: 20px; }
        ol { padding-left: 20px; }
    </style>
</head>
<body>
    <nav>
        <a href="index.html">About</a>
        <a href="news.html">News</a>
        <a href="publications.html">Publications</a>
        <a href="projects.html">Projects</a>
        <a href="cv.html">CV</a>
    </nav>
    <h1>Abed Khorasani</h1>
    <p>abedkh@northwestern.edu | Phone: 312-776-5420</p>
    
    <h2>Profile Highlights</h2>
    <ul>
        <li>Focused on advancing personalized neurorehabilitation through the integration of wearable sensors, adaptive AI models, and neuromodulation techniques to improve motor and sensory recovery in real-world, home-based settings.</li>
        <li>Currently leading three translational research projects: (1) gamified myoelectric neurorehabilitation for stroke recovery, (2) development of wearable and flexible EMG sensor technologies, and (3) closed-loop, non-invasive spinal cord stimulation for post-stroke motor rehabilitation.</li>
        <li>Clinical collaborations with Northwestern Memorial Hospital and Shirley Ryan AbilityLab; academic collaborations with Northwestern University and the University of Washington; and industry collaborations with Myomo Inc., MindMaze Inc., and the Rogers Group (Sibel Health, Inc.).</li>
        <li>Author of 40 peer-reviewed journal and conference publications, including 30 as first author; inventor on one neural engineering patent; and co-investigator or co–principal investigator on four funded grants.</li>
        <li>Mentored one Ph.D. student and three master’s students; taught graduate and undergraduate courses in neuroscience and electrical engineering.</li>
    </ul>
    
    <h2>Research Positions</h2>
    <ul>
        <li>Northwestern University, Chicago, USA - Research Assistant Professor, Department of Neurology (08/2025 – Present)
            <ul>
                <li>Leading development of a closed-loop, non-invasive spinal cord stimulation system for stroke rehabilitation, with stimulation parameters dynamically adjusted based on user intent decoded from multi-channel EMG signals.</li>
                <li>Designing and validating flexible, wearable EMG and IMU sensor platforms to quantify motor behavior, muscle coordination, and recovery during real-world, home-based rehabilitation.</li>
                <li>Developing adaptive myoelectric training strategies, including AI-driven task personalization, to enhance motor learning, adherence, and functional recovery during at-home therapy.</li>
                <li>Developing AI-assisted, time-series language model (TSLM)–based systems that integrate wearable biosignals and patient feedback to provide real-time, therapist-like guidance and improve adherence during home-based myoelectric rehabilitation.</li>
            </ul>
        </li>
        <li>Northwestern University, Chicago, USA - Postdoctoral Research Fellow, Department of Neurology (09/2021 – 08/2025) Advisor: Dr. Marc Slutzky
            <ul>
                <li>Led a randomized clinical trial (n=59) deploying the Myoelectric Interface for Neurorehabilitation (MINT) as a home-based therapy for chronic stroke, demonstrating clinically meaningful improvements in arm function and a 76% reduction in abnormal muscle co-activation.</li>
                <li>Integrated sleep-stage targeting using EEG and wearable sensors with myoelectric training to enhance motor memory consolidation.</li>
                <li>Collaborated with UT Southwestern to extend MINT to lower-limb rehabilitation, demonstrating improved gait mechanics and reduced abnormal hip–knee co-activation.</li>
                <li>Conducted mechanistic studies identifying early emergence of abnormal shoulder synergies after stroke.</li>
            </ul>
        </li>
        <li>Kerman University of Medical Sciences, Kerman, Iran - Research Assistant Professor, Department of Neuroscience (11/2019 – 09/2021)
            <ul>
                <li>Designed and fabricated multi-channel neural acquisition and stimulation systems for small-animal research.</li>
                <li>Led AI-driven projects developing unsupervised and adaptive decoding algorithms for stable brain–computer interfaces and real-time artifact rejection.</li>
            </ul>
        </li>
        <li>University of Washington, Seattle, USA - Research Fellow, Department of Rehabilitation Medicine (02/2017 – 03/2018) Advisor: Dr. Chet Moritz
            <ul>
                <li>Contributed to development of a brain–computer–spinal interface to restore forelimb movement after spinal cord injury.</li>
                <li>Co-developed implantable FPGA-based hardware for real-time neural decoding and stimulation.</li>
                <li>Designed online noise and artifact removal methods for intracortical recordings in freely moving animals.</li>
            </ul>
        </li>
        <li>Iran University of Science and Technology, Tehran, Iran - Research Scientist, Department of Biomedical Engineering (09/2013 – 01/2017) Advisor: Dr. Mohammad Reza Daliri
            <ul>
                <li>Developed a real-time brain–machine interface to decode motor cortex activity for robotic arm control in freely behaving rodents.</li>
            </ul>
        </li>
        <li>Iran University of Science and Technology, Tehran, Iran - Research Scientist, Department of Biomedical Engineering (09/2010 – 07/2012) Advisor: Dr. Abbas Erfanian
            <ul>
                <li>Studied intramuscular functional electrical stimulation to restore walking in rodent models of paralysis.</li>
                <li>Designed adaptive, closed-loop stimulation controllers to mitigate muscle fatigue and improve locomotor outcomes.</li>
            </ul>
        </li>
    </ul>
    
    <h2>Education</h2>
    <ul>
        <li>Ph.D. in Electrical Engineering - Bioelectric, Iran University of Science and Technology, Tehran, Iran (09/2013 – 08/2018) Honors: Best PhD Thesis in Neuroscience Thesis: Control of External Devices Based on the Motor Cortex Local Field Potentials</li>
        <li>M.Sc. in Biomedical Engineering - Bioelectric, Iran University of Science and Technology, Tehran, Iran (09/2009 – 07/2012) Thesis: Control of Rat Walking with Intramuscular Functional Electrical Stimulation</li>
        <li>B.Sc. in Electrical Engineering - Electronics, University of Kerman, Kerman, Iran (09/2004 – 09/2009) Honors: Ranked 2nd in class Thesis: Remote Control of Home Devices through Telephone Line</li>
    </ul>
    
    <h2>Research Interests</h2>
    <ul>
        <li>Neural engineering</li>
        <li>Stroke rehabilitation</li>
        <li>Spinal cord injury rehabilitation</li>
        <li>Neural control of movement</li>
        <li>Hardware implementation of closed-loop neural interfaces</li>
        <li>Adaptive neural interfaces</li>
    </ul>
    
    <h2>Skills and Abilities</h2>
    <ul>
        <li>Clinical Skills: Experience with electrophysiology in epilepsy and tumor patients, as well as acute and chronic stroke rehabilitation.</li>
        <li>Animal Models: Cranial and spinal implants for chronic electrophysiology in rodents.</li>
        <li>Rehabilitation Techniques: Brain-spinal interface, spinal cord stimulation, peripheral nerve stimulation, functional electrical stimulation, myoelectric computer interface (MyoCI), MRI-guided Transcranial Magnetic Stimulation (TMS), targeted memory reactivation (TMR).</li>
        <li>Hardware and Software Engineering: Circuit & PCB design (Altium Designer, EAGLE, PSpice, Proteus), MATLAB (Advanced), LabVIEW (Advanced), SIMULINK, CodeVision, AVR, Arduino, ActiveHDL, CorelDraw, Adobe Illustrator, Adobe Premiere.</li>
        <li>Neural Systems: Blackrock Microsystems, Multichannel Systems, Tucker-Davis Technologies, A-M Systems, Med Associates, Delsys Trigno.</li>
        <li>Programming Languages: MATLAB (Advanced), Python (Advanced), C (Intermediate), C++ (Intermediate).</li>
        <li>Languages: English (Fluent), Persian (Native).</li>
    </ul>
</body>
</html>

<!-- File: news.html -->
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Abed Khorasani - News</title>
    <style>
        body { font-family: Arial, sans-serif; margin: 20px; line-height: 1.6; }
        nav { background: #f0f0f0; padding: 10px; margin-bottom: 20px; }
        nav a { margin-right: 20px; text-decoration: none; color: #333; }
        nav a:hover { text-decoration: underline; }
        h1, h2 { color: #333; }
        ul { list-style-type: disc; padding-left: 20px; }
    </style>
</head>
<body>
    <nav>
        <a href="index.html">About</a>
        <a href="news.html">News</a>
        <a href="publications.html">Publications</a>
        <a href="projects.html">Projects</a>
        <a href="cv.html">CV</a>
    </nav>
    <h1>News</h1>
    <ul>
        <li>2026–2027: Awarded Querrey InQbation Lab – MedTech Studio grant ($50,000) as PI for Prototype development, clinical validation, and health economics analysis of the Myoelectric Interface for Neurorehabilitation (MINT).</li>
        <li>2026–2028: Awarded Meta Reality Labs grant ($150,000) as Co-I for Optimizing Myoelectric Interface Learning in Individuals with Intact and Injured Central Nervous Systems.</li>
        <li>2025: First Place, Q MedTech Studio Competition; supported by the Kellogg Q Business Research Fellowship.</li>
        <li>2025: Travel Award, Cleveland NeuroDesign Entrepreneurs Workshop, Cleveland, Ohio, USA.</li>
        <li>2024: Talk - Improving Motor Recovery after Stroke by Combining MINT with TMR during Sleep, Society for Neuroscience (SFN), Chicago, USA.</li>
        <li>2024: Talk - Insights from Implementing Wearable Technologies for Stroke Rehabilitation Outside Research Labs, MR3 Network Scientific Retreat, Virtual, USA.</li>
        <li>2024: Talk - Neural Interfaces for Recovering Movement After Stroke and Spinal Cord Injury, Loyola University, Chicago, USA.</li>
        <li>2023: Travel Award, Big Data Analysis (ACNN) Conference, Columbus, Ohio, USA.</li>
        <li>2020: Travel Award, Neural Control of Movement (NCM) Conference, Toyama, Japan ($1,500).</li>
        <li>2020: Talk - Recent Advances in Brain-Spinal Cord Interfaces, Frontiers in Neural Sciences (FNS), Tehran, Iran.</li>
        <li>2020: Talk - Neural Engineering: Brain Control of Spinal Cord Stimulation, Institute for Research in Fundamental Science (IPM), Tehran, Iran.</li>
        <li>2019–2021: Awarded Kerman University of Medical Sciences grant ($3,000) as PI for Developed a neural conditioning system integrating brain–computer interface and reward-area stimulation.</li>
        <li>2019–2021: Awarded National Institute of Medical Sciences Research grant ($8,200) as PI for Co-developed an implantable neural interface to restore forelimb movement in rodent models.</li>
        <li>2019: Travel Award, NCM Conference, Dubrovnik, Croatia ($1,500).</li>
        <li>2018: Best PhD Thesis in Neuroscience, Basic and Clinical Neuroscience Society, Tehran, Iran.</li>
        <li>2018: Talk - Introduction to Various Fields in Biomedical Engineering, Azad University of Kerman, Kerman, Iran.</li>
        <li>2018: Talk - Restoration of Movement after Spinal Cord Injury, University of Kerman, Kerman, Iran.</li>
        <li>2017: Research Scholarship, Paul G. Allen Family Foundation, USA ($38,400).</li>
        <li>2010: Top 2 Rank, B.Sc. Electrical Engineering, University of Kerman, Iran.</li>
    </ul>
</body>
</html>

<!-- File: publications.html -->
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Abed Khorasani - Publications</title>
    <style>
        body { font-family: Arial, sans-serif; margin: 20px; line-height: 1.6; }
        nav { background: #f0f0f0; padding: 10px; margin-bottom: 20px; }
        nav a { margin-right: 20px; text-decoration: none; color: #333; }
        nav a:hover { text-decoration: underline; }
        h1, h2 { color: #333; }
        ol { padding-left: 20px; }
    </style>
</head>
<body>
    <nav>
        <a href="index.html">About</a>
        <a href="news.html">News</a>
        <a href="publications.html">Publications</a>
        <a href="projects.html">Projects</a>
        <a href="cv.html">CV</a>
    </nav>
    <h1>Publications</h1>
    
    <h2>Journal Papers</h2>
    <ol>
        <li>Khorasani A, Gorski CM, Hung NT, Hulsizer J, Paul V, Tomic G, Prakash PR, Park S, Houskamp EJ, Lanis J, Hunzeker M, King E, Chappel A, Jampol A, Patel P, Gallagher C, Galant R, Rucker G, Lee J, Harvey R, Roh J, Slutzky MW. (2024) Wearable Myoelectric Interface for Neurorehabilitation (MINT) to Recover Arm Function: a Randomized Controlled Trial, medRxiv.</li>
        <li>Khorasani A, Gang S, Roh J, Slutzky M. (2025) Early Emergence of Abnormal Muscle Synergies Following Stroke, Ready for submission.</li>
        <li>Khorasani A, Hulsizer J, Paul V, Gorski C, Dhaher Y, Slutzky M. (2025) Myoelectric interface for neurorehabilitation conditioning to reduce abnormal leg co-activation after stroke: a pilot study, Journal of NeuroEngineering and Rehabilitation, 21(1), 1.</li>
        <li>Ganjali M, Mehridehnavi A*, Rakhshani S, Khorasani A*. (2024) Unsupervised neural manifold alignment for stable decoding of movement from cortical signals, International Journal of Neural Systems, 34(1), 2450006 (*Corresponding authors).</li>
        <li>Kang Y*, Khorasani A*, Flint RD, Farrokhi B, Lee SW. (2023) Editorial: Neural computations for brain machine interface applications, Frontiers in Human Neuroscience, 17, 1334636 (*equal contribution).</li>
        <li>Samejima S, Hanna R, Cariappa BK, Arvizu R, Nimbalkar S, Montgomery-Walsh, Galindo SL, Henderson R, Khorasani A, Moritz CT, Kassegne S. (2022) Glassy carbon neural interface for chronic epidural stimulation in rats with cervical spinal cord injury, IEEE Transactions on Neural Systems and Rehabilitation Engineering, 31(1), 620–627.</li>
        <li>Samejima S, Ievins AM, Boissenin A, Tolley NM, Khorasani A, Mondello SE, Moritz CT. (2022) Automated lever task with minimum antigravity movement for rats with cervical spinal cord injury, Journal of Neuroscience Methods, 366(1), 109433.</li>
        <li>Samejima S*, Khorasani A*, Ranganathan V, Nakahara J, Tolley NM, Boissenin A, Shalchyan V, Daliri MR, Smith JR, Moritz CT. (2021) Brain-computer spinal interface restores upper limb function after spinal cord injury, IEEE Transactions on Neural Systems and Rehabilitation Engineering, 28(1), 17–26 (*equal contribution).</li>
        <li>Ahmadi A*, Khorasani A*, Shalchyan V, Daliri MR. (2020) State-based decoding of force signals from multi-channel local field potentials, IEEE Access, 8(1), 159089–159099 (*equal contribution).</li>
        <li>Khorasani A, Shalchyan V, Daliri MR. (2019) Adaptive artifact removal from intracortical channels for accurate decoding of force signal in freely moving rats, Frontiers in Neuroscience, 13(1), 350–358.</li>
        <li>Nimbalkar S, Castagnola E, Balasubramani A, Scarpellini A, Samejima S, Khorasani A, Boissenin A, Thongpang S, Moritz C, Kassegne S. (2018) Ultra-capacitive carbon neural probe allows simultaneous long-term electrical stimulations and high-resolution neurotransmitter detection, Scientific Reports, 8(1).</li>
        <li>Khorasani A, Foodeh R, Shalchyan V, Daliri MR. (2017) Brain control of an external device by extracting the highest force-related contents of local field potentials in freely moving rats, IEEE Transactions on Neural Systems and Rehabilitation Engineering, 26(1), 18–25.</li>
        <li>Khorasani A, Heydari N, Shalchyan V, Daliri MR. (2016) Continuous force decoding from local field potentials of the primary motor cortex in freely moving rats, Scientific Reports, 6(2).</li>
        <li>Foodeh R, Khorasani A, Shalchyan V, Daliri MR. (2016) Minimum noise estimate filter: a novel automated artifacts removal method for field potentials, IEEE Transactions on Neural Systems and Rehabilitation Engineering, 25(8), 1143–1152.</li>
        <li>Khorasani A, Daliri MR, Pooyan M. (2015) Recognition of amyotrophic lateral sclerosis disease using factorial hidden Markov model, Biomedical Engineering/Biomedizinische Technik, 61(1), 119–126.</li>
        <li>Khorasani A, Daliri MR. (2014) HMM for classification of Parkinson’s disease based on the raw gait data, Journal of Medical Systems, 38(12), 1–6.</li>
        <li>Khorasani A, Daliri MR. (2013) Estimation of neural firing rate: the wavelet density estimation approach, Biomedizinische Technik/Biomedical Engineering, 58(4), 377–386.</li>
        <li>Khorasani A, Erfanian A. (2011) Adaptive neuro-fuzzy sliding mode control of walking using intramuscular electrical stimulation in Rat (in Persian), Iranian Journal of Biomedical Engineering, 5(3), 245–255.</li>
    </ol>
    
    <h2>Conference Papers</h2>
    <ol>
        <li>Khorasani A, Gorski C, Prakash P, Huang JJ, Whitmore N, Paller KA, Slutzky MW. (2025) Integrating Sleep-Based Targeted Memory Reactivation with Myoelectric Interface Neurorehabilitation to Enhance Stroke Recovery, American Society of Neurorehabilitation (ASNR) Conference, Atlanta, GA.</li>
        <li>Khorasani A, Gorski C, Prakash P, Huang JJ, Whitmore N, Paller KA, Slutzky MW. (2025) Integrating Sleep-Based Targeted Memory Reactivation with Myoelectric Interface Training for Stroke Recovery, Neural Control of Movement (NCM) Conference, Panama City, Panama.</li>
        <li>Khorasani A, Prakash P, Gorski C, Whitmore N, Paller K, Slutzky M. (2024) Improving motor recovery after stroke by combining myoelectric interface for neurorehabilitation with targeted memory reactivation during sleep, Society for Neuroscience Annual Meeting, Chicago, IL.</li>
        <li>Ganjali M, Mehridehnavi A, Rakhshani S, Khorasani A. (2024) Comparative evaluation of neural manifolds for force decoding from intracortical neural activity, Iranian Conference on Biomedical Engineering, Tehran, Iran.</li>
        <li>Khorasani A, Gorski C, Paul V, Hulsizer J, Hung N, Prakash P, Slutzky M. (2024) Insights from implementing wearable technologies for stroke rehabilitation outside research laboratories, MR3 Network Scientific Retreat, Virtual.</li>
        <li>Khorasani A, Paul V, Hung N, Prakash P, Kovach T, Hulsizer J, Slutzky M. (2023) Improving movement in chronic stroke survivors through home-based myoelectric interface neurorehabilitation conditioning, Society for Neuroscience Annual Meeting, Washington, DC.</li>
        <li>Khorasani A, Gang S, Roh J, Slutzky M. (2023) Effects of at-home myoelectric computer interface training on abnormal synergies in severely impaired stroke patients, Advanced Computational Neuroscience Conference, Columbus, OH.</li>
        <li>Khorasani A, Paul V, Hung N, Prakash P, Kovach T, Hulsizer J, Slutzky M. (2023) Home-based myoelectric interface for neurorehabilitation (MINT) conditioning to improve movement in chronic stroke survivors, American Society of Neurorehabilitation (ASNR) Conference, Charleston, SC.</li>
        <li>Khorasani A, Paul V, Hung N, Prakash P, Kovach T, Hulsizer J, Slutzky M. (2022) Home-based training with a wearable myoelectric interface for neurorehabilitation to reduce abnormal co-activation and improve arm function in chronic stroke, Society for Neuroscience Annual Meeting, San Diego, CA.</li>
        <li>Khorasani A, Paul V, Hung N, Prakash P, Kovach T, Hulsizer J, Slutzky M. (2022) Wearable myoelectric interface for neurorehabilitation (MINT) of arm function in chronic stroke, American Society of Neurorehabilitation (ASNR) Conference, St. Louis, MO.</li>
        <li>Khorasani A, Samejima S, Shalchyan V, Daliri MR, Moritz CT. (2021) Combining generalized eigenvalue decomposing with Laplacian filtering to improve cortical decoding performance, 10th International IEEE EMBS Neural Engineering Conference, Virtual.</li>
        <li>Ranganathan V, Nakahara J, Samejima S, Tolley N, Khorasani A, Moritz CT, Smith JR. (2019) Neural closed-loop implantable platform: a modular FPGA-based neural interface for closed-loop operation, 9th International IEEE EMBS Neural Engineering Conference, San Francisco, CA.</li>
        <li>Khorasani A, Shalchyan V, Daliri MR. (2018) Artifact removal from intracortical channels for brain-machine interface applications, Basic and Clinical Neuroscience Congress, Tehran, Iran.</li>
        <li>Samejima S, Khorasani A, Boissenin A, Ranganathan V, Smith JR, Moritz CT. (2018) Restoring graded forelimb movement after spinal cord injury with cortical-local field potential control of epidural spinal stimulation, Society for Neuroscience Annual Meeting, San Diego, CA.</li>
        <li>Oh J, Samejima S, Khorasani A, Boissenin A, Moritz CT. (2018) Simultaneous recording of micro-electrocorticography and local field potentials for decoding rat forelimb movement, 27th Annual Computational Neuroscience Meeting CNS, Seattle, WA.</li>
        <li>Samejima S, Khorasani A, Boissenin A, Ranganathan V, Smith JR, Moritz CT. (2018) Brain-controlled epidural spinal interface reanimating forelimb function in spinal cord injury, 7th International BCI Meeting, Asilomar, CA.</li>
        <li>Khorasani A, Shalchyan V, Daliri MR. (2017) Combinational intracortical decoder of forelimb force in freely moving rats, 12th Göttingen Meeting, Göttingen, Germany.</li>
        <li>Khorasani A, Heydari N, Shalchyan V, Daliri MR. (2015) Continuous decoding of rat forelimb force from local field potentials, Basic and Clinical Neuroscience Congress, Tehran, Iran.</li>
        <li>Khorasani A, Hasheminezhad M, Azarbadegan M. (2015) The vital and movement signs monitoring system (in Persian), International Conference on Research in Engineering Science and Technology, Istanbul, Turkey.</li>
        <li>Khorasani A, Shalchyan V, Daliri MR. (2014) Automatic estimation of neural firing rate based on the wavelet packets (in Persian), Iranian Conference on Biomedical Engineering, Tehran, Iran.</li>
        <li>Khorasani A, Daliri MR. (2013) New wavelet-based density estimator for neural firing rate estimation, Basic and Clinical Neuroscience Congress, Tehran, Iran.</li>
        <li>Khorasani A, Erfanian A. (2013) Higher-order sliding mode control of multi-joint movement using intramuscular functional electrical stimulation, IFESS Annual Conference, Gipzukoa, Spain.</li>
        <li>Khorasani A, Erfanian A. (2012) Adaptive neuro-fuzzy sliding mode control of walking using intramuscular functional electrical stimulation, Basic and Clinical Neuroscience Congress, Tehran, Iran.</li>
        <li>Khorasani A, Erfanian A. (2011) Adaptive neuro-fuzzy control of the rat knee joint using functional electrical stimulation (in Persian), Iranian Conference on Biomedical Engineering, Tehran, Iran.</li>
    </ol>
    
    <h2>Patents</h2>
    <ul>
        <li>Moritz CT, Khorasani A, et al., University of Washington, 2023. High frequency epidural stimulation to control sensation, U.S. Patent Application 18/007,948.</li>
    </ul>
    
    <h2>Books</h2>
    <ul>
        <li>Khorasani A, Fatehi Hassan. (2013) Wavelets in LabVIEW, Arna Publication.</li>
    </ul>
</body>
</html>

<!-- File: projects.html -->
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Abed Khorasani - Projects</title>
    <style>
        body { font-family: Arial, sans-serif; margin: 20px; line-height: 1.6; }
        nav { background: #f0f0f0; padding: 10px; margin-bottom: 20px; }
        nav a { margin-right: 20px; text-decoration: none; color: #333; }
        nav a:hover { text-decoration: underline; }
        h1, h2 { color: #333; }
        ul { list-style-type: disc; padding-left: 20px; }
    </style>
</head>
<body>
    <nav>
        <a href="index.html">About</a>
        <a href="news.html">News</a>
        <a href="publications.html">Publications</a>
        <a href="projects.html">Projects</a>
        <a href="cv.html">CV</a>
    </nav>
    <h1>Projects</h1>
    <ul>
        <li><strong>Gamified Myoelectric Neurorehabilitation for Stroke Recovery</strong>: Leading a translational project focused on gamified myoelectric training to enhance motor recovery in stroke patients through home-based therapy.</li>
        <li><strong>Development of Wearable and Flexible EMG Sensor Technologies</strong>: Designing and validating flexible, wearable EMG and IMU sensor platforms to quantify motor behavior and recovery in real-world settings.</li>
        <li><strong>Closed-Loop, Non-Invasive Spinal Cord Stimulation for Post-Stroke Motor Rehabilitation</strong>: Developing a system where stimulation parameters are dynamically adjusted based on user intent decoded from EMG signals.</li>
        <li><strong>Myoelectric Interface for Neurorehabilitation (MINT)</strong>: Led a randomized clinical trial deploying MINT for chronic stroke, showing improvements in arm function; extended to lower-limb rehabilitation; integrated with sleep-stage targeting for memory consolidation.</li>
        <li><strong>AI-Assisted Time-Series Language Model (TSLM) Systems for Home-Based Rehabilitation</strong>: Integrating wearable biosignals and patient feedback to provide real-time guidance and improve adherence.</li>
        <li><strong>Unsupervised and Adaptive Decoding Algorithms for Brain-Computer Interfaces</strong>: AI-driven projects for stable BCIs and real-time artifact rejection in small-animal research.</li>
        <li><strong>Brain–Computer–Spinal Interface for Spinal Cord Injury</strong>: Contributed to restoring forelimb movement; co-developed implantable FPGA hardware; designed noise removal methods for intracortical recordings.</li>
        <li><strong>Real-Time Brain–Machine Interface for Robotic Arm Control</strong>: Decoded motor cortex activity in freely behaving rodents for robotic control.</li>
        <li><strong>Intramuscular Functional Electrical Stimulation for Paralysis</strong>: Studied stimulation to restore walking in rodent models; designed adaptive controllers to mitigate muscle fatigue.</li>
        <li><strong>Neural Conditioning System with BCI and Reward-Area Stimulation</strong>: Developed system integrating brain-computer interface and reward stimulation.</li>
        <li><strong>Implantable Neural Interface for Forelimb Movement Restoration</strong>: Co-developed interface in rodent models.</li>
    </ul>
</body>
</html>

<!-- File: cv.html -->
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Abed Khorasani - CV</title>
    <style>
        body { font-family: Arial, sans-serif; margin: 20px; line-height: 1.6; }
        nav { background: #f0f0f0; padding: 10px; margin-bottom: 20px; }
        nav a { margin-right: 20px; text-decoration: none; color: #333; }
        nav a:hover { text-decoration: underline; }
        h1, h2 { color: #333; }
        ul { list-style-type: disc; padding-left: 20px; }
        pre { white-space: pre-wrap; font-family: inherit; }
    </style>
</head>
<body>
    <nav>
        <a href="index.html">About</a>
        <a href="news.html">News</a>
        <a href="publications.html">Publications</a>
        <a href="projects.html">Projects</a>
        <a href="cv.html">CV</a>
    </nav>
    <h1>CV</h1>
    <p><a href="CV_Khorasani.pdf">Download Full CV (PDF)</a></p>
    
    <!-- Full CV text for reference -->
    <pre>
Abed Khorasani
abedkh@northwestern.edu
Phone: 312-776-5420

Profile Highlights

• Focused on advancing personalized neurorehabilitation through the integration of wearable sen-
sors, adaptive AI models, and neuromodulation techniques to improve motor and sensory recovery
in real-world, home-based settings.

• Currently leading three translational research projects: (1) gamified myoelectric neurorehabilita-
tion for stroke recovery, (2) development of wearable and flexible EMG sensor technologies, and
(3) closed-loop, non-invasive spinal cord stimulation for post-stroke motor rehabilitation.

• Clinical collaborations with Northwestern Memorial Hospital and Shirley Ryan AbilityLab; aca-
demic collaborations with Northwestern University and the University of Washington; and in-
dustry collaborations with Myomo Inc., MindMaze Inc., and the Rogers Group (Sibel Health,
Inc.).

• Author of 40 peer-reviewed journal and conference publications, including 30 as first author;
inventor on one neural engineering patent; and co-investigator or co–principal investigator on
four funded grants.

• Mentored one Ph.D. student and three master’s students; taught graduate and undergraduate
courses in neuroscience and electrical engineering.

Research Positions

• Northwestern University, Chicago, USA
08/2025 – Present
Research Assistant Professor, Department of Neurology

– Leading development of a closed-loop, non-invasive spinal cord stimulation system for stroke
rehabilitation, with stimulation parameters dynamically adjusted based on user intent decoded
from multi-channel EMG signals.

– Designing and validating flexible, wearable EMG and IMU sensor platforms to quantify motor
behavior, muscle coordination, and recovery during real-world, home-based rehabilitation.

– Developing adaptive myoelectric training strategies, including AI-driven task personalization,
to enhance motor learning, adherence, and functional recovery during at-home therapy.

– Developing AI-assisted, time-series language model (TSLM)–based systems that integrate
wearable biosignals and patient feedback to provide real-time, therapist-like guidance and
improve adherence during home-based myoelectric rehabilitation.

Northwestern University, Chicago, USA
09/2021 – 08/2025
Postdoctoral Research Fellow, Department of Neurology
Advisor: Dr. Marc Slutzky

• Led a randomized clinical trial (n=59) deploying the Myoelectric Interface for Neurorehabilita-
tion (MINT) as a home-based therapy for chronic stroke, demonstrating clinically meaningful
improvements in arm function and a 76% reduction in abnormal muscle co-activation.

1

 • Integrated sleep-stage targeting using EEG and wearable sensors with myoelectric training to
enhance motor memory consolidation.

• Collaborated with UT Southwestern to extend MINT to lower-limb rehabilitation, demonstrating
improved gait mechanics and reduced abnormal hip–knee co-activation.

• Conducted mechanistic studies identifying early emergence of abnormal shoulder synergies after
stroke.

Kerman University of Medical Sciences, Kerman, Iran
11/2019 – 09/2021
Research Assistant Professor, Department of Neuroscience

• Designed and fabricated multi-channel neural acquisition and stimulation systems for small-
animal research.

• Led AI-driven projects developing unsupervised and adaptive decoding algorithms for stable
brain–computer interfaces and real-time artifact rejection.

University of Washington, Seattle, USA
02/2017 – 03/2018
Research Fellow, Department of Rehabilitation Medicine
Advisor: Dr. Chet Moritz

• Contributed to development of a brain–computer–spinal interface to restore forelimb movement
after spinal cord injury.

• Co-developed implantable FPGA-based hardware for real-time neural decoding and stimulation.

• Designed online noise and artifact removal methods for intracortical recordings in freely moving
animals.

Iran University of Science and Technology, Tehran, Iran
09/2013 – 01/2017
Research Scientist, Department of Biomedical Engineering
Advisor: Dr. Mohammad Reza Daliri

• Developed a real-time brain–machine interface to decode motor cortex activity for robotic arm
control in freely behaving rodents.

Iran University of Science and Technology, Tehran, Iran
09/2010 – 07/2012
Research Scientist, Department of Biomedical Engineering
Advisor: Dr. Abbas Erfanian

• Studied intramuscular functional electrical stimulation to restore walking in rodent models of
paralysis.

• Designed adaptive, closed-loop stimulation controllers to mitigate muscle fatigue and improve
locomotor outcomes.

Education

• Ph.D. in Electrical Engineering - Bioelectric, Iran University of Science and Technology,
Tehran, Iran
09/2013 – 08/2018

2

 Honors: Best PhD Thesis in Neuroscience
Thesis: Control of External Devices Based on the Motor Cortex Local Field Potentials

• M.Sc. in Biomedical Engineering - Bioelectric, Iran University of Science and Technology,
Tehran, Iran
09/2009 – 07/2012
Thesis: Control of Rat Walking with Intramuscular Functional Electrical Stimulation

• B.Sc. in Electrical Engineering - Electronics, University of Kerman, Kerman, Iran 09/2004
– 09/2009
Honors: Ranked 2nd in class
Thesis: Remote Control of Home Devices through Telephone Line

Funding

• Querrey InQbation Lab – MedTech Studio, Northwestern University, USA — PI
($50,000)
2026–2027
Project: Prototype development, clinical validation, and health economics analysis of the Myo-
electric Interface for Neurorehabilitation (MINT).

• Meta Reality Labs, USA — Co-I ($150,000)
2026–2028
Project: Optimizing Myoelectric Interface Learning in Individuals with Intact and Injured Cen-
tral Nervous Systems.

• Kerman University of Medical Sciences, Kerman — PI ($3,000)
2019–2021
Project: Developed a neural conditioning system integrating brain–computer interface and reward-
area stimulation.

• National Institute of Medical Sciences Research, Tehran — PI ($8,200)
2019–2021
Project: Co-developed an implantable neural interface to restore forelimb movement in rodent
models.

Honors and Awards

• First Place, Q MedTech Studio Competition; supported by the Kellogg Q Business Research
Fellowship
2025

• Travel Award, Cleveland NeuroDesign Entrepreneurs Workshop, Cleveland, Ohio, USA
2025

• Travel Award, Big Data Analysis (ACNN) Conference, Columbus, Ohio, USA
2023

• Travel Award, Neural Control of Movement (NCM) Conference, Toyama, Japan ($1,500)
2020

• Travel Award, NCM Conference, Dubrovnik, Croatia ($1,500)
2019

• Best PhD Thesis in Neuroscience, Basic and Clinical Neuroscience Society, Tehran, Iran
2018

• Research Scholarship, Paul G. Allen Family Foundation, USA ($38,400)
2017

• Top 2 Rank, B.Sc. Electrical Engineering, University of Kerman, Iran
2010

Research Interests

• Neural engineering, Stroke rehabilitation, Spinal cord injury rehabilitation, Neural control of
movement, Hardware implementation of closed-loop neural interfaces, Adaptive neural interfaces

3

 Skills and Abilities

• Clinical Skills: Experience with electrophysiology in epilepsy and tumor patients, as well as
acute and chronic stroke rehabilitation.

• Animal Models: Cranial and spinal implants for chronic electrophysiology in rodents.

• Rehabilitation Techniques: Brain-spinal interface, spinal cord stimulation, peripheral nerve
stimulation, functional electrical stimulation, myoelectric computer interface (MyoCI), MRI-
guided Transcranial Magnetic Stimulation (TMS), targeted memory reactivation (TMR).

• Hardware and Software Engineering: Circuit & PCB design (Altium Designer, EAGLE,
PSpice, Proteus), MATLAB (Advanced), LabVIEW (Advanced), SIMULINK, CodeVision, AVR,
Arduino, ActiveHDL, CorelDraw, Adobe Illustrator, Adobe Premiere.

• Neural Systems: Blackrock Microsystems, Multichannel Systems, Tucker-Davis Technologies,
A-M Systems, Med Associates, Delsys Trigno.

• Programming Languages: MATLAB (Advanced), Python (Advanced), C (Intermediate),
C++ (Intermediate).

• Languages: English (Fluent), Persian (Native).

Publications

Journal Papers

1. Khorasani A, Gorski CM, Hung NT, Hulsizer J, Paul V, Tomic G, Prakash PR, Park S,
Houskamp EJ, Lanis J, Hunzeker M, King E, Chappel A, Jampol A, Patel P, Gallagher C, Galant
R, Rucker G, Lee J, Harvey R, Roh J, Slutzky MW. (2024) Wearable Myoelectric Interface
for Neurorehabilitation (MINT) to Recover Arm Function: a Randomized Controlled Trial,
medRxiv.

2. Khorasani A, Gang S, Roh J, Slutzky M. (2025) Early Emergence of Abnormal Muscle Syn-
ergies Following Stroke, Ready for submission.

3. Khorasani A, Hulsizer J, Paul V, Gorski C, Dhaher Y, Slutzky M. (2025) Myoelectric interface
for neurorehabilitation conditioning to reduce abnormal leg co-activation after stroke: a pilot
study, Journal of NeuroEngineering and Rehabilitation, 21(1), 1.

4. Ganjali M, Mehridehnavi A*, Rakhshani S, Khorasani A*. (2024) Unsupervised neural man-
ifold alignment for stable decoding of movement from cortical signals, International Journal of
Neural Systems, 34(1), 2450006 (*Corresponding authors).

5. Kang Y*, Khorasani A*, Flint RD, Farrokhi B, Lee SW. (2023) Editorial: Neural computations
for brain machine interface applications, Frontiers in Human Neuroscience, 17, 1334636 (*equal
contribution).

6. Samejima S, Hanna R, Cariappa BK, Arvizu R, Nimbalkar S, Montgomery-Walsh, Galindo SL,
Henderson R, Khorasani A, Moritz CT, Kassegne S. (2022) Glassy carbon neural interface
for chronic epidural stimulation in rats with cervical spinal cord injury, IEEE Transactions on
Neural Systems and Rehabilitation Engineering, 31(1), 620–627.

4

 7. Samejima S, Ievins AM, Boissenin A, Tolley NM, Khorasani A, Mondello SE, Moritz CT.
(2022) Automated lever task with minimum antigravity movement for rats with cervical spinal
cord injury, Journal of Neuroscience Methods, 366(1), 109433.

8. Samejima S*, Khorasani A*, Ranganathan V, Nakahara J, Tolley NM, Boissenin A, Shalchyan
V, Daliri MR, Smith JR, Moritz CT. (2021) Brain-computer spinal interface restores upper
limb function after spinal cord injury, IEEE Transactions on Neural Systems and Rehabilitation
Engineering, 28(1), 17–26 (*equal contribution).

9. Ahmadi A*, Khorasani A*, Shalchyan V, Daliri MR. (2020) State-based decoding of force
signals from multi-channel local field potentials, IEEE Access, 8(1), 159089–159099 (*equal
contribution).

10. Khorasani A, Shalchyan V, Daliri MR. (2019) Adaptive artifact removal from intracortical
channels for accurate decoding of force signal in freely moving rats, Frontiers in Neuroscience,
13(1), 350–358.

11. Nimbalkar S, Castagnola E, Balasubramani A, Scarpellini A, Samejima S, Khorasani A, Boiss-
enin A, Thongpang S, Moritz C, Kassegne S. (2018) Ultra-capacitive carbon neural probe allows
simultaneous long-term electrical stimulations and high-resolution neurotransmitter detection,
Scientific Reports, 8(1).

12. Khorasani A, Foodeh R, Shalchyan V, Daliri MR. (2017) Brain control of an external device
by extracting the highest force-related contents of local field potentials in freely moving rats,
IEEE Transactions on Neural Systems and Rehabilitation Engineering, 26(1), 18–25.

13. Khorasani A, Heydari N, Shalchyan V, Daliri MR. (2016) Continuous force decoding from
local field potentials of the primary motor cortex in freely moving rats, Scientific Reports, 6(2).

14. Foodeh R, Khorasani A, Shalchyan V, Daliri MR. (2016) Minimum noise estimate filter: a
novel automated artifacts removal method for field potentials, IEEE Transactions on Neural
Systems and Rehabilitation Engineering, 25(8), 1143–1152.

15. Khorasani A, Daliri MR, Pooyan M. (2015) Recognition of amyotrophic lateral sclerosis disease
using factorial hidden Markov model, Biomedical Engineering/Biomedizinische Technik, 61(1),
119–126.

16. Khorasani A, Daliri MR. (2014) HMM for classification of Parkinson’s disease based on the
raw gait data, Journal of Medical Systems, 38(12), 1–6.

17. Khorasani A, Daliri MR. (2013) Estimation of neural firing rate: the wavelet density estimation
approach, Biomedizinische Technik/Biomedical Engineering, 58(4), 377–386.

18. Khorasani A, Erfanian A. (2011) Adaptive neuro-fuzzy sliding mode control of walking using
intramuscular electrical stimulation in Rat (in Persian), Iranian Journal of Biomedical Engi-
neering, 5(3), 245–255.

Conference Papers

1. Khorasani A, Gorski C, Prakash P, Huang JJ, Whitmore N, Paller KA, Slutzky MW. (2025)
Integrating Sleep-Based Targeted Memory Reactivation with Myoelectric Interface Neuroreha-
bilitation to Enhance Stroke Recovery, American Society of Neurorehabilitation (ASNR) Con-
ference, Atlanta, GA.

5

 2. Khorasani A, Gorski C, Prakash P, Huang JJ, Whitmore N, Paller KA, Slutzky MW. (2025)
Integrating Sleep-Based Targeted Memory Reactivation with Myoelectric Interface Training for
Stroke Recovery, Neural Control of Movement (NCM) Conference, Panama City, Panama.

3. Khorasani A, Prakash P, Gorski C, Whitmore N, Paller K, Slutzky M. (2024) Improving motor
recovery after stroke by combining myoelectric interface for neurorehabilitation with targeted
memory reactivation during sleep, Society for Neuroscience Annual Meeting, Chicago, IL.

4. Ganjali M, Mehridehnavi A, Rakhshani S, Khorasani A. (2024) Comparative evaluation of
neural manifolds for force decoding from intracortical neural activity, Iranian Conference on
Biomedical Engineering, Tehran, Iran.

5. Khorasani A, Gorski C, Paul V, Hulsizer J, Hung N, Prakash P, Slutzky M. (2024) Insights
from implementing wearable technologies for stroke rehabilitation outside research laboratories,
MR3 Network Scientific Retreat, Virtual.

6. Khorasani A, Paul V, Hung N, Prakash P, Kovach T, Hulsizer J, Slutzky M. (2023) Improving
movement in chronic stroke survivors through home-based myoelectric interface neurorehabili-
tation conditioning, Society for Neuroscience Annual Meeting, Washington, DC.

7. Khorasani A, Gang S, Roh J, Slutzky M. (2023) Effects of at-home myoelectric computer
interface training on abnormal synergies in severely impaired stroke patients, Advanced Compu-
tational Neuroscience Conference, Columbus, OH.

8. Khorasani A, Paul V, Hung N, Prakash P, Kovach T, Hulsizer J, Slutzky M. (2023) Home-
based myoelectric interface for neurorehabilitation (MINT) conditioning to improve movement in
chronic stroke survivors, American Society of Neurorehabilitation (ASNR) Conference, Charleston,
SC.

9. Khorasani A, Paul V, Hung N, Prakash P, Kovach T, Hulsizer J, Slutzky M. (2022) Home-based
training with a wearable myoelectric interface for neurorehabilitation to reduce abnormal co-
activation and improve arm function in chronic stroke, Society for Neuroscience Annual Meeting,
San Diego, CA.

10. Khorasani A, Paul V, Hung N, Prakash P, Kovach T, Hulsizer J, Slutzky M. (2022) Wearable
myoelectric interface for neurorehabilitation (MINT) of arm function in chronic stroke, American
Society of Neurorehabilitation (ASNR) Conference, St. Louis, MO.

11. Khorasani A, Samejima S, Shalchyan V, Daliri MR, Moritz CT. (2021) Combining generalized
eigenvalue decomposing with Laplacian filtering to improve cortical decoding performance, 10th
International IEEE EMBS Neural Engineering Conference, Virtual.

12. Ranganathan V, Nakahara J, Samejima S, Tolley N, Khorasani A, Moritz CT, Smith JR. (2019)
Neural closed-loop implantable platform: a modular FPGA-based neural interface for closed-
loop operation, 9th International IEEE EMBS Neural Engineering Conference, San Francisco,
CA.

13. Khorasani A, Shalchyan V, Daliri MR. (2018) Artifact removal from intracortical channels for
brain-machine interface applications, Basic and Clinical Neuroscience Congress, Tehran, Iran.

14. Samejima S, Khorasani A, Boissenin A, Ranganathan V, Smith JR, Moritz CT. (2018) Restor-
ing graded forelimb movement after spinal cord injury with cortical-local field potential control
of epidural spinal stimulation, Society for Neuroscience Annual Meeting, San Diego, CA.

6

 15. Oh J, Samejima S, Khorasani A, Boissenin A, Moritz CT. (2018) Simultaneous recording of
micro-electrocorticography and local field potentials for decoding rat forelimb movement, 27th
Annual Computational Neuroscience Meeting CNS, Seattle, WA.

16. Samejima S, Khorasani A, Boissenin A, Ranganathan V, Smith JR, Moritz CT. (2018) Brain-
controlled epidural spinal interface reanimating forelimb function in spinal cord injury, 7th In-
ternational BCI Meeting, Asilomar, CA.

17. Khorasani A, Shalchyan V, Daliri MR. (2017) Combinational intracortical decoder of forelimb
force in freely moving rats, 12th G¨ottingen Meeting, G¨ottingen, Germany.

18. Khorasani A, Heydari N, Shalchyan V, Daliri MR. (2015) Continuous decoding of rat forelimb
force from local field potentials, Basic and Clinical Neuroscience Congress, Tehran, Iran.

19. Khorasani A, Hasheminezhad M, Azarbadegan M. (2015) The vital and movement signs mon-
itoring system (in Persian), International Conference on Research in Engineering Science and
Technology, Istanbul, Turkey.

20. Khorasani A, Shalchyan V, Daliri MR. (2014) Automatic estimation of neural firing rate based
on the wavelet packets (in Persian), Iranian Conference on Biomedical Engineering, Tehran, Iran.

21. Khorasani A, Daliri MR. (2013) New wavelet-based density estimator for neural firing rate
estimation, Basic and Clinical Neuroscience Congress, Tehran, Iran.

22. Khorasani A, Erfanian A. (2013) Higher-order sliding mode control of multi-joint movement us-
ing intramuscular functional electrical stimulation, IFESS Annual Conference, Gipzukoa, Spain.

23. Khorasani A, Erfanian A. (2012) Adaptive neuro-fuzzy sliding mode control of walking us-
ing intramuscular functional electrical stimulation, Basic and Clinical Neuroscience Congress,
Tehran, Iran.

24. Khorasani A, Erfanian A. (2011) Adaptive neuro-fuzzy control of the rat knee joint using
functional electrical stimulation (in Persian), Iranian Conference on Biomedical Engineering,
Tehran, Iran.

Patents

• Moritz CT, Khorasani A, et al., University of Washington, 2023.
High frequency epidural
stimulation to control sensation, U.S. Patent Application 18/007,948.

Books

• Khorasani A, Fatehi Hassan. (2013) Wavelets in LabVIEW, Arna Publication.

Talks

• Improving Motor Recovery after Stroke by Combining MINT with TMR during Sleep, Society
for Neuroscience (SFN), Chicago, USA
2024

• Insights from Implementing Wearable Technologies for Stroke Rehabilitation Outside Research
Labs, MR3 Network Scientific Retreat, Virtual, USA
2024

7

 • Neural Interfaces for Recovering Movement After Stroke and Spinal Cord Injury, Loyola Univer-
sity, Chicago, USA
2024

• Recent Advances in Brain-Spinal Cord Interfaces, Frontiers in Neural Sciences (FNS), Tehran,
Iran
2020

• Neural Engineering: Brain Control of Spinal Cord Stimulation, Institute for Research in Funda-
mental Science (IPM), Tehran, Iran
2020

• Introduction to Various Fields in Biomedical Engineering, Azad University of Kerman, Kerman,
Iran
2018

• Restoration of Movement after Spinal Cord Injury, University of Kerman, Kerman, Iran
2018

Service

Program Committee Member

• Poster Session Reviewer, Computation and Data Exchange (CoDEx) Conference, Northwestern
University
2025

• Guest Editor, Frontiers in Neurology
2023

• Associate Editor, Frontiers in Human Neuroscience
2022
Duties: Collaborated with four editors to edit 58 papers submitted to a special issue on ”Neural
Computations for Brain Machine Interface Applications.”

• Conference Board, 9th Basic and Clinical Neuroscience Congress (BCNC)
2020
Duties: As an executive committee member, contributed to a three-day congress with 32 diverse
panels and keynote talks, engaging 90 national and international speakers across topics like brain
mapping and COVID-19’s neurological effects.

• Chair, Cognitive Impairment Treatment Panel, 8th Clinical Neuroscience Congress
2019

• Chair, Brain Decoding Panel, 7th Basic and Clinical Neuroscience Congress
2018

Reviewer

• Neurorehabilitation and Neural Repair
2025–Present

• Journal of NeuroEngineering and Rehabilitation
2025–Present

• Entropy
2024–Present

• Computer Methods in Biomechanics and Biomedical Engineering
2024–Present

• Applied Sciences
2023–Present

• Sensors
2023–Present

• Addiction Biology
2023–Present

• Journal of Neural Engineering
2023–Present

• Frontiers in Neuroscience
2021–Present

• Medical Journal of Mashhad University of Medical Sciences
2021–Present

8

 • Basic and Clinical Neuroscience Conference
2020

• Basic and Clinical Neuroscience Journal
2019–Present

• Informatics in Medicine Unlocked, Elsevier
2020–Present

• IEEE 5th Conference on Knowledge-based Engineering and Innovation
2019

• 26th Iranian Conference on Biomedical Engineering
2019

• Iranian Journal of Biomedical Engineering
2018–Present

Teaching and Mentoring Experience

Teaching

• Workshop Instructor, Machine Learning in Neuroscience, Institute for Research in Funda-
mental Sciences (PhD and MSc students)
2024
Duties: Delivered workshops on machine learning applications in neuroscience, covering advanced
techniques for data analysis and modeling for PhD and MSc students.

• Instructor, AI for Neuroscience, Kerman University of Medical Sciences (PhD students) 2021
Duties: Taught PhD neuroscience students fundamental concepts in signal processing, neural
networks, and brain decoding/encoding techniques, emphasizing practical AI applications.

• Instructor, Computational Neuroscience, Kerman University of Medical Sciences (PhD stu-
dents)
2021
Duties: Instructed PhD students on core computational neuroscience topics, including neural
encoding/decoding, information theory, biophysical neuron models, network dynamics, synaptic
plasticity, spike-train analysis, and computational modeling.

• Lab Instructor, Electrophysiology Lab, Iran University of Science and Technology (MSc stu-
dents)
2014
Duties: Guided MSc students in electrophysiological techniques, focusing on recording and ana-
lyzing biosignals such as EMGs, ECGs, and body pressure.

• Workshop Instructor, Surgical Operations for Micro Wire Array Implantation on Rats, Iran
University of Science and Technology (MSc students)
2014
Duties: Trained MSc students in surgical techniques for implanting micro wire arrays in rats,
enabling biosignal recording for neuroscience research.

• Instructor, Fundamentals of Electrical Engineering 1 & 2, Valiasr University of Rafsanjan (BSc
students)
2013
Duties: Taught BSc students foundational electrical engineering concepts, including Ohm’s Law,
Kirchhoff’s Laws, DC/AC circuit analysis, impedance, resonance, transient and frequency re-
sponse, Laplace transforms, RLC circuits, power calculations, circuit theorems, and mesh/nodal
analysis.

• Instructor, Electrical Circuits 1 & 2 and Electronics, Azad University of Rafsanjan (BSc stu-
dents)
2013
Duties: Delivered lectures on circuit analysis, electronic components, and their applications,
fostering practical problem-solving skills in BSc students.

9

 • Instructor, Electrical Machines 1 & 2, Misagh University of Rafsanjan (BSc students)
2013
Duties: Instructed BSc students on DC machines and transformers, covering construction, op-
erating principles, performance characteristics, efficiency, voltage regulation, and equivalent cir-
cuits.

Mentoring

• Mohammad Ganjali, PhD student in BME, Isfahan University of Medical Sciences
2021–2024
Developing unsupervised stable BCI decoders using neural manifolds (PhD program co-advisor)
Outcome: Published one peer-reviewed paper and two conference papers under my guidance.
Awarded two travel grants.

• Fatemeh Daneshvar, MSc student in BME, Iran University of Science and Technology 2022–2024
Brain signal biomarkers related to recovery after spinal cord injury (MSc program co-advisor)

• Behnam Soufi, MSc student in BME, Iran University of Science and Technology
2021–2023
Designing stable BCIs using combinational LFP-spike neural manifolds (MSc program co-advisor)

• Ali Mohseni, MSc student in BME, Iran University of Science and Technology
2021–2022
Decoding workload information from iEEG signals in working memory tasks (MSc program co
