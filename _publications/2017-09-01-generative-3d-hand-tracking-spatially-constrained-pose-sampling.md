---
title: "Generative 3D Hand Tracking with Spatially Constrained Pose Sampling"
collection: publications
category: conferences
permalink: /publication/2017-09-01-generative-3d-hand-tracking-spatially-constrained-pose-sampling
excerpt: ''
date: 2017-09-01
venue: 'British Machine Vision Conference (BMVC 2017)'
paperurl: 'http://users.ics.forth.gr/~argyros/mypapers/2017_09_BMVC_RDSRoditak.pdf'
citation: 'K. Roditakis, A. Makris and A.A. Argyros, "Generative 3D Hand Tracking with Spatially Constrained Pose Sampling", In British Machine Vision Conference (BMVC 2017), BMVA, London, UK, September 2017.'
---

**Abstract:**

We present a method for 3D hand tracking that exploits spatial constraints in the form of end effector (fingertip) locations. The method follows a generative, hypothesize-and-test approach and uses a hierarchical particle filter to track the hand. In contrast to state of the art methods that consider spatial constraints in a soft manner, the proposed approach enforces constraints during the hand pose hypothesis generation phase by sampling in the sl Reachable Distance Space (RDS). This sampling produces hypotheses that respect both the hands' dynamics and the end effector locations. The data likelihood term is calculated by measuring the discrepancy between the rendered 3D model and the available observations. Experimental results on challenging, ground truth-annotated sequences containing severe hand occlusions demonstrate that the proposed approach outperforms the state of the art in hand tracking accuracy.