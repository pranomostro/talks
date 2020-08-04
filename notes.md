Quantitative Forecasting
========================

Prerequisites
-------------

Who is not comfortable with the idea that beliefs are probabilistic
in nature?

### If Not

Introduction
------------

We often want to know what is going to happen, whether in relation to
politics, the climate or in fact altruism. We call this forecasting
or predicting.

Question: How can we find out how good we are at forecasting, and how
can we get better?

Basic Concepts
--------------

Track records, aggregating & evaluating forecasts, fast adaption failure

Example chosen:

Some people decided that global thermonuclear war was a good idea, and
started it, but you survived.

Really bad radioactive rain you want to avoid (when deciding in the
morning to go out and scavenge the ruins).

### Calibration

#### Minimal Model

Draw calibration graph

Predict 90% probability for radioactive rain every day for 100 days

→ 30% of the days there actually is radioactive rain.

Not well calibrated on 80%

You change your base-rate to 30%.

#### Slightly More Complex Model

You get a feeling that cloud color is important

Green clouds → 60%
Yellow clouds → 30%
No clouds → 10%

Results:

Green clouds → 70%
Yellow clouds → 50%
No clouds → 10%

⇒ You adjust

#### Overconfidence

#### Underconfidence

### Resolution

### Brier Score

Given: `$n$` predictions, set `$o=\{o_{1}, \cdots, o_{n}\} \subset \{0,1\}$`
of outcomes, set `$f=\{f_{1}, \cdots, f_{n}\} \subset (0;1)$` of
forecasts.

Formula: `$BS=\frac{1}{n}\sum_{t=1}^{n}(f_{t}-o_{t})^2$`

Mean squared error of the forecasts.

Real-Life
----------

Example from Metaculus

### Formulating a Question

#### Resolution Criteria

#### Closing Date

#### Resolving Date

Strategies
----------

### Intuitions

### Base Rates

### Algorithms

#### Linear Extrapolations

#### Quadratic and Exponential Growth

#### Scientific Models

Applications
------------

### Generally

Big, complicated & dynamic systems where we don't have good mathematical
models yet (clock vs. cloud axis), but human intuition is good.

### Effective Altruism

### Meteorology

### Geopolitics

### Policy

Problems
--------

Real-Life Initiatives
---------------------

### Forecasting Platforms

* Metaculus
* Predictionbook
* Foretold

### Prediction Markets

* PredictIt
* Augur
