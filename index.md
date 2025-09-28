---
layout: project_page
permalink: /

title: Seeing What Matters<br> Attentional (Mis-)Alignment Between Humans and AI in VR-Simulated Prediction of Driving Accidents
authors:
    Hoe Sung Ryu$^{1}$, Uijong Ju$^{3}$, Christian Wallraven$^{1,2}$
affiliations:
    Department of Artificial Intelligence, Korea University, Seoul, Korea$^{1}$<br>
    Department of Brain and Cognitive Engineering, Korea University , Seoul, Korea$^{2}$<br>
    Department of Information Display, Kyung Hee University, Seoul, Korea$^{3}$
video: https://youtu.be/
# paper: https://www.cs.virginia.edu/~robins/Turing_Paper_1936.pdf
# code: https://github.com/topics/turing-machines
---

--- 

![Overview of the research framework](/static/image/overview.png)
<!-- <script>
document.querySelectorAll('img[src="/static/image/overview.png"]').forEach(img => {
  img.style.width = "80%";      // 크기 조절
  img.style.height = "70%";      // 크기 조절
  img.style.display = "block";  // 블록 요소로 변환
  img.style.margin = "0 auto";  // 좌우 자동 마진 → 가운데 정렬
});
</script> -->


<script>
document.querySelectorAll('img[src="/static/image/overview.png"]').forEach(img => {
  // 크기 + 정렬
  img.style.width = "80%";      // 크기 조절
  img.style.height = "70%";      // 크기 조절
  img.style.display = "block";
  img.style.margin = "0 auto";
  // 캡션 추가
  const caption = document.createElement("div");
  caption.textContent = "Overview of the research framework";
  caption.style.textAlign = "center";
  caption.style.fontSize = "17px";
  caption.style.color = "#555";
  caption.style.marginTop = "6px";
  img.insertAdjacentElement("afterend", caption);
});
</script>


--- 
<!-- Using HTML to center the abstract -->
<div class="columns is-centered has-text-centered">
    <div class="column is-four-fifths">
        <h2>Abstract</h2>
        <div class="content has-text-justified">
This study explores how human and AI visual attention differ in a short-term prediction task, particularly in the moments before an accident is about to happen. Since real-world studies of this kind would pose ethical and safety risks, we employed virtual reality (VR) to simulate an accident scenario. In the scenario, the driver approaches a fork in the road, knowing that one path would lead off a cliff crashing the car fatally---as the fork comes closer, the other, safe, path is suddenly blocked by trees, forcing the driver to make a split-second decision where to go. A total of N=71 drivers completed the task, and we asked another N=30 observers to watch short video clips leading up to the final event and to predict which way the driver would take. We then compared both prediction accuracy as well as attention patterns—how focus is distributed across objects—with AI systems, including vision language models (VLMs) and vision-only models. We found that overall, prediction performance increased as the accident time point approached; interestingly, humans fared better than AI systems overall except for the final time period just before the event. We also found that humans adapted their attention dynamically, shifting focus to important scene elements before an event, whereas AI attention remained static, overlooking key details of the scene. Importantly, as the accident time point approached, human-AI attentional alignment <em><strong>decreased</strong></em>, even though both types of models improved in prediction accuracy. Despite distinct temporal trajectories---vision-only models declining from an early advantage and VLMs peaking in the middle---both models achieved low to zero alignment with human attention. These findings highlight a critical dissociation: AI models make accurate predictions, but rely on visual strategies diverging from human processing, underscoring a gap between explainability and task performance.
        </div>
    </div>
</div>

---

## Research Question
“Can AI models achieve human-level future anticipation and visual attention strategies when predicting accident dilemmas in driving scenario?”

## Objective
Benchmark prediction performance and analyze attentional alignment gaps between humans and AI models in VR-simulated critical scenario.

## Significance
In safety-critical domains, our work demonstrates that performance metrics alone are insufficient to judge model reliability, highlighting that human-aligned attention is essential for trustworthy AI deployment in high-stakes scenarios.

<!-- ## Reference: 
- [1] Ju et al. (2020). Acoustic cues increase situational awareness in accident situations: A VR car-driving study, IEEE transactions on intelligent transportation systems. -->


<!-- ## Citation
```
@article{turing1936computable,
  title={On computable numbers, with an application to the Entscheidungsproblem},
  author={Turing, Alan Mathison},
  journal={Journal of Mathematics},
  volume={58},
  number={345-363},
  pages={5},
  year={1936}
}
``` -->
