# Munger Mental Models

A comprehensive collection of Charlie Munger's lattice of mental models, organized by discipline and interconnected for practical application. Learn to think across multiple domains the way one of history's greatest investors does.

Charlie Munger famously advocates for building a latticework of mental models drawn from every major discipline. He argues that most people are trapped in a single discipline's worldview, and that the key to great decision-making is carrying models from physics, biology, psychology, economics, mathematics, and engineering all at once. This repository catalogs those models, explains their origins, and shows how to apply them in practice. For a daily review system that helps you internalize these models over time, visit [KeepRule](https://keeprule.com), where Munger's wisdom is organized into actionable decision-making rules.

## Model Categories

### Psychology (12 Models)
- Incentive and Reinforcement
- Denial and Cognitive Dissonance
- Social Proof and Imitation
- Reciprocation Tendency
- Consistency and Commitment Bias
- Liking and Association Bias
- Authority Misinfluence
- Availability Cascade
- Stress-Induced Mental Shifts
- Deprival Super-Reaction
- Contrast Misreaction
- Lollapalooza Effects

### Economics (8 Models)
- Supply and Demand
- Competitive Advantage and Moats
- Opportunity Cost
- Marginal Utility
- Specialization and Comparative Advantage
- Creative Destruction
- Tragedy of the Commons
- Agency Problems

### Mathematics (6 Models)
- Compounding
- Inversion
- Permutations and Combinations
- Algebraic Equivalence
- Decision Trees
- Bayes Theorem

### Biology (5 Models)
- Natural Selection and Adaptation
- Ecosystems and Niches
- Red Queen Effect
- Symbiosis and Parasitism
- Survivorship Bias in Evolution

## Installation

```bash
# Clone the repository
git clone https://github.com/henu-wang/munger-mental-models.git
cd munger-mental-models

# Install dependencies
pip install -r requirements.txt

# Build the cross-reference index
python index_models.py
```

## Usage

### Exploring Models

```bash
# Browse all models in a category
python explore.py --category psychology

# View a specific model with examples
python explore.py --model "inversion"

# Find models relevant to a decision scenario
python explore.py --scenario "evaluating a business acquisition"
```

### Building Your Lattice

```python
from munger import Lattice

lattice = Lattice()
lattice.add_model("inversion")
lattice.add_model("incentive-reinforcement")
lattice.add_model("competitive-advantage")

# Analyze a problem through multiple lenses
analysis = lattice.analyze("Should we enter a new market?")
for model, insight in analysis.items():
    print(f"{model}: {insight}")
```

### Syncing with KeepRule

Export your model collection for spaced repetition review:

```bash
python export.py --format keeprule --category all
```

Build a lasting practice of multi-disciplinary thinking with [KeepRule](https://keeprule.com), which helps you review and internalize mental models on a consistent schedule.

## Repository Structure

```
munger-mental-models/
├── models/
│   ├── psychology/
│   ├── economics/
│   ├── mathematics/
│   ├── biology/
│   ├── physics/
│   ├── engineering/
│   └── philosophy/
├── examples/
│   ├── berkshire-decisions/
│   ├── business-analysis/
│   └── everyday-application/
├── tools/
│   ├── explore.py
│   ├── lattice.py
│   └── export.py
├── tests/
├── requirements.txt
└── README.md
```

## Contributing

We encourage contributions that expand and improve the model collection:

1. Fork the repository
2. Create a branch (`git checkout -b model/new-model-name`)
3. Write the model explanation following our template format
4. Include real-world examples from Munger's speeches, Berkshire meetings, or your own analysis
5. Submit a pull request

We particularly welcome contributions that show how multiple models interact in a single decision, which Munger calls lollapalooza effects.

## Further Resources

Munger's mental models are just the beginning of a lifetime practice. To systematically build your own latticework and review it regularly, explore [KeepRule](https://keeprule.com) for a curated collection of investment and decision-making principles from Buffett, Munger, and other legendary thinkers.

## License

MIT License - see [LICENSE](LICENSE) for details.
