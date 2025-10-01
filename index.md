---
layout: project_page
permalink: /

title: "SCENEDERELLA: Text-Driven 3D Scene Generation for Realistic Artboard"
authors:
  - name: "Jungmin Lee"
    url: "https://sites.google.com/vilab.cau.ac.kr/jungminleeshomepage/%ED%99%88"
    affiliation: 1
    is_coauthor: true
  - name: "Haeun Noh"
    url: "https://sites.google.com/view/haeunnoh/%ED%99%88"
    affiliation: 1
    is_coauthor: true
  - name: "Jaeyoon Lee"
    url: "https://sites.google.com/vilab.cau.ac.kr/jaeyoonlee"
    affiliation: 1
  - name: "Jongwon Choi"
    url: "https://scholar.google.co.kr/citations?user=F3u9qHcAAAAJ&hl=ko"
    affiliation: 1
  
affiliations:
  - id: 1
    school: "Chung-Ang University"


paper: https://drive.google.com/file/d/1cMaETOQGHbarZg9cqOc6X7N-96pwtC7s/view?usp=sharing
demo: https://6679fcf3d6588f6543.gradio.live
homepage: https://www.vilab.cau.ac.kr/
---

<!-- Using HTML to center the abstract -->
<div class="columns is-centered has-text-centered">
    <div class="column is-four-fifths">
        <h2>Abstract</h2>
        <div class="content has-text-justified">
As global media and Video-on-Demand (VOD) markets expand, efficiently producing high-quality 3D scenes has become a key challenge. 
Our study named "SCENEDERELLA" generates 3D scenes useful for the film industry using simple text prompts. 
Since traditional diffusion models create fantastic images, they have limitations in generating scenes truly desired by real-world users. 
However, fine-tuning the clip encoder of the diffusion model enables the production of realistic 2D scenes for users. 
Once the initial 2D scenes align with the user's conceptual expectations, we construct 3D scenes using a depth estimator and 3D Gaussian Splatting. 
The study successfully demonstrates the generation of 3D movie scenes based on various movie scripts. 
Our method overcomes the limitations of traditional physical set production and offers a new approach that enables the rapid creation of diverse scenes. 
Additionally, it can be used as a pre-visualization video to attract investment in movies and dramas. 
Our approach is expected to introduce a new paradigm in content production, with film, gaming, and advertising.
        </div>
    </div>
</div>

---



## Background
With the growing demand in global media and Video-on-Demand (VOD) industries, efficiently producing high-quality 3D scenes has become an essential challenge. Traditional methods, such as physical set construction and 3D modeling by hand, are time-consuming and costly. While diffusion models have shown promise in generating stunning images, they often lack the flexibility and precision needed to meet specific industry demands.

## Objective
SCENEDERELLA aims to democratize 3D scene creation by providing a user-friendly platform where anyone can iteratively refine their ideas through text-based prompts. Users can regenerate scenes until they find the one that matches their vision. Once satisfied, the system seamlessly converts the 2D scene into a fully realized 3D environment. This workflow ensures that both novices and professionals can translate their creative ideas into tangible, 3D representations with minimal effort.


## Key Ideas
1. **Iterative Scene Refinement**: Users can repeatedly regenerate 2D scenes based on their text prompts until the output aligns with their creative vision.
2. **Personalized Scene Generation**: The system adapts to user inputs, ensuring outputs are tailored to individual preferences, whether for film, gaming, or advertising applications.

![Framework](/static/images/framework.png)
*Figure 1: A Framework of SCENEDERELLA.*


## Acknowledgment
This work was partly supported by Institute of Information & communications Technology Planning & Evaluation (IITP) grant funded by the Korea government(MSIT) (2021-0-01341, Artificial Intelligence Graduate School Program(Chung-Ang University)) and the MSIT(Ministry of Science and ICT), Korea, under the Graduate School of Metaverse Convergence support program(IITP-2023(2024)-RS-2024-00418847) supervised by the IITP.

## Citation
```bibtex
@inproceedings{lee2025scenederella,
  title={SCENEDERELLA: Text-Driven 3D Scene Generation for Realistic Artboard},
  author={Lee, Jungmin and Noh, Haeun and Lee, Jaeyoon and Choi, Jongwon},
  booktitle={2025 IEEE International Conference on Consumer Electronics (ICCE)},
  pages={1--6},
  year={2025},
  organization={IEEE}
}

