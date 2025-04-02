---
layout: default
---

## Introduction


<style>
  .bio-container {
    max-width: 600px;
    margin: auto;
    font-size: 16px;
  }

  .bio-text {
    overflow: hidden;
    max-height: 100px; /* Show only part of the text initially */
    transition: max-height 0.3s ease-out;
  }

  .bio-text.expanded {
    max-height: 500px; /* Adjust based on your text length */
  }

  .read-more-btn {
    background-color: #0073e6;
    color: white;
    padding: 8px 12px;
    font-size: 14px;
    border: none;
    cursor: pointer;
    border-radius: 5px;
    margin-top: 5px;
    margin-bottom: 15px;
  }

  .read-more-btn:hover {
    background-color: #005bb5;
  }
</style>

<div class="bio-container">
  <p class="bio-text" id="bio">
Geophysicist with a Master’s degree in Geophysics and Geodynamics, specializing in seismology, and strong research foundation in the application of geophysical techniques. My technical expertise includes geophysical data processing, analysis, and interpretation, along with proficiency in Shell scripting, Unix-based operating systems and command-line tools. I’m also skilled in Python programming, with a focus on solving geophysical problems. I am passionate about bridging research and practical applications, proficient in tackling complex challenges, and contributing to meaningful projects.    
  </p>
  <button class="read-more-btn" onclick="toggleBio()">Read More</button>
</div>

<script>
  function toggleBio() {
    var bio = document.getElementById("bio");
    var btn = document.querySelector(".read-more-btn");

    if (bio.classList.contains("expanded")) {
      bio.classList.remove("expanded");
      btn.textContent = "Read More";
    } else {
      bio.classList.add("expanded");
      btn.textContent = "Read Less";
    }
  }
</script>

* * *
### Core Skills

- Programming
- Geophysics
- Data Science

### Hobbies and Interests

- Outdoor activities
- Coding and scripting
- Teaching and Mentoring

## Resume

Please read my resume [here](./resume.html).
Or you can [📄 download My resume](assets/resume.pdf){: .btn .btn-primary }


## Projects

### Joint inversion of receiver functions and dispersion curves

As a part of a national grant to study the sedimentary basins in northern Brazil, in order to provide a better tectonic understanding of the on and offshore basins. I participated in this project by applying a joint inversion of teleseismic receiver functions and dispersion curves. Read more about it [here](joint_inversion.html)


### Development of the Herglotz-Wiechert algorithm in Python

I developed, in Python, a computational code to implement an inversion methodology based on the solution of the Herglotch-Wiechert algorithm and teste the performance of the method thorugh the measurement and inversion of P-wave travel times for a set of earthquakes recorded at the Brazilian Seismographic Network. Read more about it [here](./HW.html).

### Geophysical surveys
During my bachelor, I worked on several [geophysical surveys](./geophysical_surveys.html), with a range of purposes. See on the link some snapshots and objectives of these surveys.


## Research & Publications

+ [Bachelor Thesis](https://repositorio.ufrn.br/bitstream/123456789/34358/1/AvaliacaoInversaoHerglotz_Barbosa_2018.pdf)
+ [Master Thesis](https://repositorio.ufrn.br/bitstream/123456789/49492/1/EstruturalitosfericaBacia_Barbosa_2022.pdf)
+ [Published Article](https://www.sciencedirect.com/science/article/abs/pii/S0264370722000564): Lithospheric S-velocity structure of the on-shore Potiguar Basin, NE Brazil: High heat-flow in an aborted rift


## Contact information

* [Email me](mailto:thabita.sofiagomes@gmail.com)
* [Linkedin](https://www.linkedin.com/in/thabita-barbosa/)



