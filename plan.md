# Website Plan: Geometric Distributional Deep Learning Workshop

## Workshop Information

**Title**: Bridging Optimal Transport, Learning and Structured Data: Toward Geometric Distributional Learning

**Tagline**: Learning with structured data and probability distributions: synergies between optimal transport and geometric deep learning.

**Conference**: NeurIPS 2026

**Location**: Palais des Congrès de Paris, France

**Workshop Date**: December 12-13, 2026

**Expected Attendance**: 100-250 in-person + 50-150 online

---

## Abstract

Modern machine learning increasingly relies on representing complex data through their **geometric structure** or **probability distribution**. Geometric Deep Learning has made it possible to encode symmetries, invariances, equivariance, and relational information in non-Euclidean domains, such as graphs and manifolds, with many successful applications, ranging from protein structure prediction to neuroscience. In parallel, viewing data or features as probability distributions has led to powerful methodologies in deep learning. In particular, **optimal transport** (OT) provides a natural framework for comparing, aligning, and transforming data distributions, and has contributed to notable advances in generative modeling, attention-based architectures, and representation learning.

Although these perspectives are connected, they are often developed separately: geometric models typically focus on the structure of the underlying domain, while most distributional methods operate in Euclidean spaces or treat geometry only implicitly. Yet, recent works show that combining geometric and distributional principles can lead to more effective learning models.

This workshop will focus on this emerging area that we call **Geometric Distributional Deep Learning**: learning systems that jointly model the geometry and distributional nature of data, features and representations. The goal is to bring together researchers in geometric deep learning, computational optimal transport, generative modeling, graph and manifold learning, and deep learning theory around a shared question:

> *How can geometry and distributions be combined to design more scalable, efficient, and interpretable models for structured data?*

---

## Key Dates

| Milestone | Date |
|-----------|------|
| Call for contributions opens | July 13, 2026 |
| Submission deadline | August 29, 2026 (AoE) |
| Notification of decisions | September 29, 2026 (AoE) |
| Final program announced | October 16, 2026 |
| Workshop | December 12-13, 2026 |

---

## Confirmed Invited Speakers (7)

| Name | Affiliation | Website | Topics |
|------|-------------|---------|--------|
| David Alvarez-Melis | Harvard / Microsoft Research | https://dmelis.github.io/ | ML & OT for structured data |
| Anna Calissano | UCL | https://annacalissano.com/ | Statistical analysis of graph distributions |
| Marco Cuturi | Apple / ENSAE-CREST | https://marcocuturi.net/ | Scalable OT, generative models |
| Stefanie Jegelka | TU Munich / MIT | https://people.csail.mit.edu/stefje/ | Geometric ML, graphs, multi-modal learning |
| Nicolas Keriven | CNRS / Inria | https://nkeriven.github.io/ | ML & signal processing on graphs |
| Soheil Kolouri | Vanderbilt University | https://skolouri.github.io/ | Computational OT, sliced OT, geometric DL |
| Clarice Poon | University of Warwick | https://cmhsp2.github.io/ | Inverse OT, sparse optimization, imaging |

---

## Organizers (6)

| Name | Affiliation | Email | Website |
|------|-------------|-------|---------|
| Clément Bonet | Ecole Polytechnique (CMAP) | clement.bonet.mapp@polytechnique.edu | https://clbonet.github.io/ |
| Julie Delon | ENS / Université Paris Cité | julie.delon@ens.fr | https://judelo.github.io/ |
| Nina Miolane | UC Santa Barbara | ninamiolane@ucsb.edu | https://www.ninamiolane.com/ |
| Youssef Mroueh | IBM Research | mroueh@us.ibm.com | https://research.ibm.com/people/youssef-mroueh |
| Kimia Nadjahi | CNRS / ENS | kimia.nadjahi@ens.fr | https://kimiandj.github.io/ |
| Justin Solomon | MIT | jsolomon@mit.edu | https://people.csail.mit.edu/jsolomon/ |

---

## Schedule (Full Day)

### Morning

| Time | Event |
|------|-------|
| 9:00-9:05 | Opening |
| 9:05-9:35 | Invited: Marco Cuturi |
| 9:35-10:05 | Invited: Clarice Poon |
| 10:05-10:30 | Coffee break |
| 10:30-11:00 | Invited: Nicolas Keriven |
| 11:00-11:30 | Contributed talks (x2) |
| 11:30-12:30 | Poster session I |
| 12:30-14:00 | Lunch break |

### Afternoon

| Time | Event |
|------|-------|
| 14:00-14:30 | Invited: Stefanie Jegelka |
| 14:30-15:00 | Invited: Soheil Kolouri |
| 15:00-15:30 | Contributed talks (x2) |
| 15:30-16:00 | Coffee break |
| 16:00-16:30 | Invited: Anna Calissano |
| 16:30-17:00 | Invited: David Alvarez-Melis |
| 17:00-18:00 | Poster session II |
| 18:00-18:05 | Closing remarks |

---

## Topics of Interest

1. **Geometry-aware Transport & Distributional Modeling**
   - Adapting OT to graphs, manifolds, physical systems

2. **Neural Architectures for Distributions on Non-Euclidean Domains**
   - Layers/models for probability distributions on graphs/manifolds
   - Distributional representations in GNNs

3. **Scalable Computation on Structured Spaces**
   - Sliced methods, entropic regularization, neural approximations
   - Making geometry-aware methods usable at scale

4. **Generative Models & Flow-Based Methods**
   - Diffusion on manifolds, normalizing flows on structured spaces

5. **Applications**
   - Molecular modeling
   - Climate & weather prediction
   - Neuroscience
   - Physical sciences

---

## Submission Tracks

- **Long-format**: 5-8 pages
- **Short-format**: 2-4 pages (early-stage contributions)
- All accepted papers: poster presentation
- Selected papers: oral presentation (4 contributed talks)
- Review: Double-blind via OpenReview

---

## Design Specifications (Different from EDPM Workshop)

### Color Scheme: Deep Purple + Coral

```css
:root {
    --primary: #5b21b6;        /* Deep purple */
    --primary-light: #7c3aed;  /* Violet */
    --primary-dark: #4c1d95;   /* Darker purple */
    --accent: #f97316;         /* Coral/Orange */
    --accent-light: #fb923c;   /* Light coral */
    --accent-dark: #ea580c;    /* Dark coral */
    --text: #1e1b4b;           /* Dark indigo */
    --text-light: #6366f1;     /* Indigo */
    --background: #faf5ff;     /* Very light purple */
    --surface: #ffffff;
}
```

### Style Differences from EDPM Workshop

| Aspect | EDPM (Teal & Gold) | This Workshop (Purple & Coral) |
|--------|-------------------|-------------------------------|
| Primary color | Teal (#0d5c63) | Deep Purple (#5b21b6) |
| Accent color | Gold (#d4a03c) | Coral (#f97316) |
| Hero style | Gradient background | Geometric pattern overlay |
| Cards | Rounded corners | More angular, subtle shadows |
| Typography | Playfair Display | Could use Space Grotesk or DM Sans |
| Icons | Feather icons | Geometric/abstract icons |
| Section dividers | Simple lines | Geometric shapes |

### Page Sections

1. **Hero** - Workshop title, NeurIPS 2026 Paris, geometric background pattern
2. **About** - Workshop abstract and goals
3. **Topics** - Key research areas (with geometric icons)
4. **Schedule** - Single-day tabbed or accordion schedule
5. **Speakers** - Photo grid with affiliations
6. **Organizers** - Photo grid with affiliations
7. **Call for Papers** - Submission tracks, dates, OpenReview link
8. **Venue** - Palais des Congrès de Paris info
9. **Footer** - NeurIPS logo, contact info

---

## File Structure

```
workshop-distributional-geom-dl/
├── website/
│   ├── index.html
│   ├── css/
│   │   └── style.css
│   ├── js/
│   │   └── main.js
│   └── images/
│       ├── speakers/
│       └── organizers/
├── main (1).tex          (existing)
└── plan.md               (this file)
```

---

## Implementation Steps

1. Create index.html with all sections
2. Create style.css with purple/coral theme and geometric design
3. Create main.js for navigation and interactions
4. Download speaker photos from their websites
5. Download organizer photos from their websites
6. Test responsive design
7. Deploy to GitHub Pages

---

## Notes

- Contact email: TBD (could use one of the organizer emails or create workshop-specific)
- OpenReview link: TBD (will be created after workshop acceptance)
- NeurIPS provides broadcast support for online attendees
- Travel support available for junior researchers
