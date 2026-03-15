# ML Interview Prep

Technical deep-dives on optimization and generalization for Applied Scientist interviews.

## Articles

### [Optimization Algorithms](optimization_blog.html)
GD, SGD, Momentum, RMSProp, Adam, AdamW — implementation, theory, and trade-offs.

**Covers:** NumPy implementations from scratch, bias correction derivation, when to use SGD vs Adam, debugging convergence, learning rate schedules, real interview questions from Anthropic/Google.

### [Loss Landscapes](loss_landscape_blog.html)
Why sharp minima hurt generalization and how optimizers shape the loss surface.

**Covers:** Hessian eigenvalues, flat vs sharp minima, batch size effects, SAM, why SGD beats Adam on vision, measuring sharpness in practice.

## Study Approach

Week 1-2: Implement each optimizer in NumPy, compare to PyTorch  
Week 2-3: Connect optimizer behavior to loss landscape geometry  
Week 3-4: Practice interview questions, debugging scenarios

## Key Concepts

**Must know:**
- Implement SGD, Momentum, Adam from scratch
- Explain Adam's bias correction mathematically
- When SGD generalizes better than Adam (and why)
- Sharp vs flat minima (Hessian eigenvalues)
- Batch size → sharpness → generalization
- Debugging: gradient norms, LR warmup, weight decay

**Papers:**
- Adam (Kingma & Ba, 2014)
- AdamW (Loshchilov & Hutter, 2017)
- SAM (Foret et al., 2020)
- Large-batch sharp minima (Keskar et al., 2016)

---

Written for mid-senior Applied Scientists targeting OpenAI, Anthropic, Google, Meta.
