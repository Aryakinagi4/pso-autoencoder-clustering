# Algorithm Workflow

## Step 1 — Preprocessing

- Clean dataset
- Apply Min-Max scaling
- Convert to numerical matrix

---

## Step 2 — Dimensionality Reduction

An Autoencoder neural network is trained to:

- Compress 13,561 dimensions
- Preserve essential structural patterns
- Reduce noise
- Improve clustering efficiency

Encoder → Latent Space Representation → Decoder

The latent representation is used for clustering.

---

## Step 3 — Elbow Method

The Elbow Method is applied to determine optimal K.

For each K:
- Compute Within-Cluster Sum of Squares (WCSS)
- Identify inflection point

---

## Step 4 — Clustering

Two approaches were evaluated:

### Baseline
- K-Means clustering

### Proposed Hybrid
- PSO-based centroid optimization
- Fitness based on intra-cluster distance minimization

---

## Step 5 — Evaluation

Metrics:

- Davies–Bouldin Index
- Silhouette Score
- Execution time comparison
- Sector distribution analysis
