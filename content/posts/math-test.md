---
title: "RL Math Theory Test"
date: 2026-02-01
draft: false
math: true
---

### 策略梯度公式测试

我们来验证一下手动注入的 KaTeX 是否工作：

$$
\nabla_\theta J(\theta) = E_{\tau \sim \pi_\theta} \left[ \sum_{t=0}^T \nabla_\theta \log \pi_\theta(a_t|s_t) A^{\pi_\theta}(s_t, a_t) \right]
$$

行内公式测试：$\pi_\theta(a|s)$