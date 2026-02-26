# Paper Note Template (SISR)

## Basic Info
- **Paper title:**
- **Authors:**
- **Year / Venue:**
- **Link (arXiv / DOI / project page):**
- **Code / Pretrained:**
- **Category:** CNN / Transformer / GAN-Perceptual / Real-world / Efficient
- **Task setting:** SISR / x2 / x4 / x8 | bicubic / real-world / blind

## 1. One-sentence takeaway
(用一句话说清这篇论文“到底做了什么、解决了什么痛点”。)

## 2. Problem & Motivation
- What problem is addressed?
- Why is it important / what is missing in prior work?

## 3. Method (What they do)
- **Backbone / overall architecture:**
- **Key modules / blocks:**
- **Upsampling strategy:** (e.g., pixelshuffle / transpose conv / etc.)
- **Any special design:** (attention / frequency / prior / degradation modelling)

## 4. Training (How they train)
- **Loss functions:** (L1/L2/perceptual/GAN/etc.)
- **Optimiser & schedule:**
- **Patch size / batch size (if given):**
- **Data augmentation:**
- **Any tricks:** (EMA, mixed precision, etc.)

## 5. Data & Degradation
- **Train dataset(s):**
- **Test dataset(s):**
- **Degradation model:** (bicubic / blur+noise+JPEG / unknown / estimated)

## 6. Evaluation & Results
- **Metrics:** PSNR / SSIM / LPIPS / runtime / params / FLOPs
- **Main results (copy key numbers):**
- **Where it wins / where it loses:**
- **Any ablation highlights:**

## 7. Strengths & Weaknesses (Critical view)
**Strengths**
- 
- 

**Weaknesses / Risks / Questions**
- 
- 

## 8. Reproducibility Notes
- Can I reproduce it easily? (Y/N + why)
- Any missing details?
- What would I need to run it? (data, compute, dependencies)

## 9. How this helps MY dissertation
- **Use as baseline?** (Y/N)
- **What idea can I reuse/adapt?**
- **What experiment should I replicate first?**
- **What would be my “small improvement” angle?** (optional)

## 10. Figure/Table worth re-creating
(写：论文里哪张图/表最值得在你 report 里复刻，为什么。)

## 11. Keywords (for searching later)
(e.g., transformer, degradation, blind SR, efficient SR, frequency, attention)
