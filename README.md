# 3D Printed Modular Acoustic Panel

## Author
Vasil B. Botev

Sofia, Bulgaria  
28.05.2024

## Abstract
The demand for cost-effective, customizable acoustic solutions has led to innovative approaches in material design and manufacturing. This study investigates the development and performance of 3D printed modular acoustic panels using Fused Deposition Modeling (FDM) technology. Our focus is on creating a low-cost, easily customizable solution accessible to anyone with a 3D printer and basic tools. The panels were designed and fabricated with varying geometric patterns to optimize sound absorption and diffusion. Acoustic measurements conducted in a previously untreated room showed significant improvements in reducing reverberation times, room distortion, and improving sound clarity and absorption. This research highlights the potential of 3D printed acoustic panels as a viable and affordable alternative for effective acoustic treatment in various settings.

## Introduction
Acoustic panels manage sound within environments such as recording studios, home theaters, office spaces, and classrooms. They absorb or diffuse sound waves, reducing noise, controlling reverberation, and improving sound clarity. Traditional acoustic panels, typically made from fiberglass, mineral wool, and foam, are effective but can be costly and offer limited customization. 3D printing, especially Fused Deposition Modeling (FDM), offers a promising alternative by enabling the creation of complex shapes and patterns optimized for sound absorption and diffusion. This technology reduces material waste, lowers production costs, and democratizes production, making it accessible to anyone with a 3D printer.

## Methods
The primary design of the 3D printed modular acoustic panels combines sound reflection and absorption. A parametric cell design serves as the fundamental building block, with each cell housing acoustic filling material to enhance sound absorption. The dimensions of the cells (70x70 mm with a variable height of 12-120 mm) define the effective frequency range of the diffuser (143 Hz to 4.9 kHz). Each cell is topped with a cap featuring micro-openings and filled with silicone fiber material. Modules, each consisting of 16 cells in a 4x4 grid, can be combined to create larger panels. The design process utilized Autodesk Fusion 360 and OpenSCAD, with iterative testing to refine functionality and material efficiency. Modules were printed using PLA on a Voron 2.4 printer.

## Results
Acoustic measurements showed significant improvements in the treated room's acoustic performance. The SPL graphs indicated smoother responses with amplitude reductions up to 3 dB at specific frequencies. Room distortion was reduced, especially at lower frequencies. The clarity graph showed an average increase of +3 dB across almost all frequency bands. RT-60 graphs demonstrated decreased reverberation times, with reductions averaging over 30% in several key frequency bands. Impulse response graphs revealed significant reductions in reflected sounds from 250 Hz to 8 kHz, confirming the panels' effectiveness.

## Future Research
Future research could explore varying cell sizes, configurations, and thicknesses, as well as different materials and cap designs. Investigations into different filler materials and backing structures could further optimize sound absorption and diffusion. Experimental methods should include controlled acoustic environments and advanced measurement techniques, supported by computer simulations. These studies could enhance the panels' performance for various applications, such as recording studios, home theaters, and public spaces.

## References
1. Li, Y., & Assouar, B. M. (2016). Acoustic metasurface-based perfect absorber with deep subwavelength thickness. *Applied Physics Letters, 108*(6), 063502.
2. Dorra, J. (n.d.). 3D-printable sound absorbers. GitHub. Retrieved July 8, 2024, from https://github.com/juliendorra/3D-printable-sound-absorbers
