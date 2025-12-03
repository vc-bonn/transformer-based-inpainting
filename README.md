<h1 align="center" id="heading">Transformer-Based Inpainting for Real-Time 3D Streaming in Sparse Multi-Camera Setups</h1>

<p align="center">
    <p align="center">
		<b><a href="https://cg.cs.uni-bonn.de/person/m-sc-leif-van-holland">Leif Van Holland</a></b>
        &nbsp;·&nbsp;
		<b><a href="https://cg.cs.uni-bonn.de/person/m-sc-domenic-zingsheim">Domenic Zingsheim</a></b>
        &nbsp;·&nbsp;
		<b><a href="https://cg.cs.uni-bonn.de/person/m-sc-mana-takhsha">Mana Takhsha</a></b>
        &nbsp;·&nbsp;
        <b><a href="https://cg.cs.uni-bonn.de/person/dr-hannah-droege">Hannah Dröge</a></b>
        &nbsp;·&nbsp;
        <b><a href="https://cg.cs.uni-bonn.de/person/dr-patrick-stotko">Patrick Stotko</a></b>
        &nbsp;·&nbsp;
        <b><a href="https://cg.cs.uni-bonn.de/person/dr-markus-plack">Markus Plack</a></b>
        &nbsp;·&nbsp;
        <b><a href="https://cg.cs.uni-bonn.de/person/prof-dr-reinhard-klein">Reinhard Klein</a></b>
    </p>
    <p align="center">
        University of Bonn
    </p>
    <h3 align="center">WACV 2026</h3>
    <h3 align="center">
        Paper (arxiv)
        &nbsp; | &nbsp;
        <a href="https://cg.cs.uni-bonn.de/publication/holland-2026-transformer-based">Project Page</a>
    </h3>
    <div align="center"></div>
</p>

<p align="center">
    <img src="./assets/pipeline.png" alt="teaser" width="100%">
</p>

## Abstract

High-quality 3D streaming from multiple cameras is crucial for immersive experiences in many AR/VR applications. The limited number of views - often due to real-time constraints - leads to missing information and incomplete surfaces in the rendered images. Existing approaches typically rely on simple heuristics for the hole filling, which can result in inconsistencies or visual artifacts. We propose to complete the missing textures using a novel, application-targeted inpainting method independent of the underlying representation as an image-based post-processing step after the novel view rendering. The method is designed as a standalone module compatible with any calibrated multi-camera system. For this we introduce a multi-view aware, transformer-based network architecture using spatio-temporal embeddings to ensure consistency across frames while preserving fine details. Additionally, our resolution-independent design allows adaptation to different camera setups, while an adaptive patch selection strategy balances inference speed and quality, allowing real-time performance. We evaluate our approach against state-of-the-art inpainting techniques under the same real-time constraints and demonstrate that our model achieves the best trade-off between quality and speed, outperforming competitors in both image and video-based metrics.

## Code Release

The full source code will be released soon.

## Acknowledgements

This work was supported by the European Regional Development Fund (ERDF) and the State of North Rhine-Westphalia as part of the operational program EFRE/JTF-Programm NRW 2021-2027. The project, titled 'Gen-AIvatar', was funded under the NEXT.IN.NRW competition with the grant agreement No. EFRE-20801085.

Additionally, it has been funded by the Federal Ministry of Education and Research of Germany and the state of North-Rhine Westphalia as part of the Lamarr-Institute for Machine Learning and Artificial Intelligence and by the Federal Ministry of Education and Research under Grant
No. 01IS22094A WEST-AI.

<p align="center">
    <a href="https://www.in.nrw/news/next-2024-11-25"><img src="./assets/nrw.png" alt="IN.NRW INNOVATIONSFÖRDERAGENTUR" width="30%"></a>
    &nbsp;&nbsp;&nbsp;&nbsp;
    <a href="https://www.mkw.nrw/innovationswettbewerb-nextinnrw-land-und-eu-foerdern-innovative-projekte-mit-rund-42-millionen-euro"><img src="./assets/ministry.jpg" alt="Ministerium für Wirtschaft, Industrie, Klimaschutz und Engergie des Landes Nordrhein-Westfalen" width="30%"></a>
    &nbsp;&nbsp;&nbsp;&nbsp;
    <a href="https://www.efre.nrw/en/easy-to-make/find-support/nextinnrw-innovation-competition"><img src="./assets/eu.png" alt="Kofinanziert von der Europäischen Union" width="30%"></a>
</p>
