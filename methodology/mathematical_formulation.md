# Mathematical Formulation

## Autoencoder

Encoder:

z = f(Wx + b)

Decoder:

x' = g(W'z + b')

Loss Function:

L = ||x - x'||²

Objective:
Minimize reconstruction error to obtain compact latent representation.

---

## Particle Swarm Optimization (PSO)

Velocity Update:

vᵢ(t+1) = w vᵢ(t)  
           + c₁ r₁ (pbestᵢ - xᵢ(t))  
           + c₂ r₂ (gbest - xᵢ(t))

Position Update:

xᵢ(t+1) = xᵢ(t) + vᵢ(t+1)

Where:

- w → inertia weight
- c₁, c₂ → cognitive & social coefficients
- r₁, r₂ → random factors
- pbest → personal best
- gbest → global best

---

## Clustering Fitness Function

Fitness = Sum of intra-cluster distances

Objective:
Minimize distance between data points and centroids.

---

## Evaluation Metrics

### Davies–Bouldin Index (DBI)

Lower DBI → Better cluster separation

### Silhouette Score

Higher Silhouette Score → Better clustering structure
