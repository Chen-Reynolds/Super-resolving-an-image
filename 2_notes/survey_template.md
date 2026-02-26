# Paper Note — <Title>

## 0. Metadata
- **Citation**: <authors, venue, year>
- **Link**: <doi/arxiv/project>
- **Paper type**: Survey / Review / Position / Tutorial
- **Topic**: <e.g., SISR / VSR / Real-world SR / Efficient SR>
- **My purpose**: Why am I reading this *now*?

## 1. One-sentence takeaway
> 用一句话说清：它解决/梳理了什么问题，给了什么框架/结论（尽量可验证）。

## 2. Problem framing (作者怎么定义问题)
- **Task definition** (inputs/outputs):
- **Assumptions** (paired data? synthetic degradation? real-world?):
- **Why this matters** (applications + constraints):
- **What is *not* covered** (explicit exclusions):

## 3. Taxonomy / Structure (这篇综述怎么分门别类)
> 先照抄它的目录骨架，再写“你觉得这个骨架好/坏在哪里”。

- **Top-level categories**:
  - A:
  - B:
  - C:

### 3.1 Is this taxonomy *useful*?
- **Strengths**: (e.g., goal-oriented, method-oriented, covers real-world, etc.)
- **Weaknesses**: (e.g., overlaps, unclear boundaries, missing a major branch)
- **Alternative taxonomy** (if I had to re-organise in 3 buckets, what would they be?)

## 4. Core technical dimensions (综述里反复出现的“技术主轴”)
> 对大多数 SR survey 都适用：数据/退化/上采样/网络/损失/评估/效率/泛化。

### 4.1 Data & Degradation
- **Datasets mentioned** (train/test):
- **Degradation models** (synthetic vs real):
- **Key pain points**: (domain gap, pairing difficulty, etc.)

### 4.2 Upsampling / Reconstruction pipeline
- **Pipeline families**:
  - pre-upsampling
  - post-upsampling
  - progressive
  - iterative up-down
- **Typical modules**:
- **Failure cases / artifacts**:

### 4.3 Model families (按它的分类写：CNN/GAN/Transformer/…)
For each family:
- **Representative models** (3–8 is enough):
- **Core idea** (what changed vs previous generation?)
- **What it improves** (PSNR? perceptual? robustness? speed?)
- **Hidden assumptions** (data, scale, degradation, compute)

### 4.4 Losses / Objectives
- Pixel losses:
- Perceptual/content losses:
- GAN/adversarial:
- Frequency-domain / priors:
- **What is optimised vs what is evaluated?** (are they aligned?)

### 4.5 Evaluation & Metrics
- **Full-reference**: PSNR / SSIM / LPIPS / …
- **No-reference**: (if mentioned)
- **Subjective**: MOS / user study
- **Protocol details**: (Y channel? crop? scale? benchmark)
- **What metrics might be misleading here?**

### 4.6 Efficiency & Deployment (if relevant)
- Params / FLOPs / latency:
- Hardware assumptions:
- Real-time constraints:
- Trade-offs stated by authors:

## 5. Evidence table (Claims → Evidence)
> 这是“critical thinking”的核心：把“结论”拆成可检验的命题。

| Claim (作者主张) | Evidence (对照/实验/引用) | Setting (data, scale, degradation) | Metric | My verdict |
|---|---|---|---|---|
| | | | | strong / ok / weak |

**Red flags checklist**
- Does the evidence match the claim scope?
- Are baselines strong and fair?
- Any cherry-picked visuals / missing failure cases?
- Any protocol detail that could inflate metrics?

## 6. What I learned (transferable)
- **Concepts/definitions** I will reuse:
- **A good figure/table** worth replicating:
- **A benchmark/protocol** I should adopt:

## 7. Limitations & gaps (作者写的 + 你补的)
- **Stated limitations**:
- **Unstated limitations** (my analysis):
- **Open problems** (rank top 3 by importance for *my* project):

## 8. How this changes my dissertation direction
- **Relevance** to my topic:
- **What I will copy** (method/protocol/taxonomy):
- **What I will avoid**:
- **New questions** raised:

## 9. Quote bank (optional, short)
> 只摘关键短句，避免长段复制；标注页码。
- p.__: “...”
