# ML Deep Dives

Technical articles on machine learning — from first principles to interview-ready depth.

## Transformer Series

- [The Attention Revolution](attention_revolution.html) — From RNNs to self-attention, vanishing gradients, LSTM/GRU, Bahdanau & Luong attention
- [Transformer Architecture End-to-End](transformer_architecture.html) — Every component: encoder, decoder, Q/K/V, FFN, residuals, LayerNorm, causal masking, cross-attention
- [Modern Transformer Extensions](modern_transformer_extensions.html) — Flash Attention, KV-Cache, MQA/GQA, MoE, RoPE, ALiBi, speculative decoding, Mamba/SSMs
- [Gradient Flow Through the Transformer](gradient-flow-through-transformer.html) — Backprop through residuals, LayerNorm, attention, causal mask, embeddings, weight tying, MoE routing, training dynamics

## ML Fundamentals

- [ML Core Concepts: A Deep Dive](ml_core_concepts_deep_dive.html) — Linear/logistic regression, bias-variance, regularization, gradient descent, cross-validation, feature scaling
- [Backpropagation Through Every Layer](backprop-through-every-layer.html) — Derivations for BCE+Sigmoid, Softmax+CE, BatchNorm, Dropout, L2 Regularization
- [Optimization Algorithms](optimization_blog.html) — GD, SGD, Momentum, RMSProp, Adam, AdamW — mechanics, trade-offs, NumPy implementations
- [Loss Landscapes](loss_landscape_blog.html) — Sharp vs flat minima, batch size effects, Hessian eigenvalues, SAM, optimizer-generalization connection
- [Activation Functions](activation-functions.html) — Sigmoid, Tanh, ReLU, Leaky ReLU, GELU, Swish/SiLU — formulas, derivatives, where each is used
