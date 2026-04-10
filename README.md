# OpenFlourish

> **From Foundation to Flourishing** - An open source ecosystem of AI agents designed to help humans thrive across all dimensions of well-being.

[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](CONTRIBUTING.md)
[![Community](https://img.shields.io/badge/community-welcome-blue.svg)](https://github.com/openflourish/openflourish/discussions)

---

## Note from the Creator

Hey everyone — I’m Alden.

I’m a proud husband and an even prouder dad to my son, Atlas (as of April 2026 — hopefully more kids to come). At the core, I’m building Open Flourish for him. My goal is simple: as he grows up, I want there to be a world filled with thoughtful humans and powerful tools that help him become everything he’s capable of becoming.

While this started as something deeply personal, it’s meant for everyone. I want this to be as accessible, practical, and useful as possible — something anyone can pick up and use to improve their life or help someone they care about.

There’s an idea I really believe in: a rising tide lifts all boats. My hope is that this project contributes, even in a small way, to that rising tide.

So if you’re here, I encourage you to use this platform selfishly — build things that would help you, your family, and your friends. Because when we all do that, those “selfish” contributions compound into something incredibly selfless — tools that help strangers across the world live better lives.

Why this matters:

We’re entering a world where AI and automation will dramatically increase efficiency. That’s a good thing — it’s what humans have always done: solve problems, improve systems, and build better tools.

But there’s a real challenge:
our economic systems don’t naturally guarantee that everyone benefits from that efficiency.

Businesses are designed to optimize — to produce more with less. That’s not wrong — it’s one of the reasons we’ve achieved so much progress as a society. The reality is, everything we have today exists because of that drive toward improvement.

This isn’t anti-capitalism.
It’s actually the opposite.

I believe in the power of free markets and human ingenuity. But I also believe that as AI accelerates that progress, we need to be intentional about making sure more people can share in the upside.

What Open Flourish is trying to do:

This project is a small step toward that future.

A world where:

People have access to tools that help them grow
AI supports human flourishing — not just efficiency
And individuals are guided toward better health, relationships, purpose, and much more.

I’m optimistic about what AI can do for humanity — but I also think we need to be incredibly thoughtful and intentional in how we shape it. 

One of my favorite scenes from The Dark Knight Rises is when Bruce climbs out of the pit as people chant “rise” — and to me, that’s the vision here: those who are strong enough to climb out of the pits they find themselves in turn back and throw the rope down to help others rise too.

If this project helps even one person improve their life — or helps someone build something that helps thousands — then it’s worth it.

If you’re here, I’m glad you are.

Let’s build something meaningful together 🌸 

## What is OpenFlourish?

OpenFlourish is a community-driven collection of AI agents and tools designed to support human flourishing across **Maslow's 8 levels of needs**. Each agent targets a specific dimension of well-being, helping users grow from basic needs to self-actualization and beyond. 

While Maslow’s hierarchy isn’t perfect and certainly has its flaws, I believe it provides a powerful and practical framework—offering enough structure to help people grow in a balanced way and make meaningful, measurable progress toward a more fulfilling life.

### The Vision

Most AI optimizes for efficiency. We believe AI should optimize for **human flourishing**.

```
🌟 Transcendence      ← Beyond self, serving others
🌳 Self-Actualization ← Becoming your best self
🎨 Aesthetic          ← Beauty, harmony, creativity
🧠 Cognitive          ← Learning, curiosity, growth
⭐ Esteem             ← Confidence, achievement, respect
💜 Belonging          ← Love, connection, community
🛡️ Safety             ← Security, stability, health
🫀 Physiological      ← Sleep, nutrition, movement
```

---

## Quick Start

### Take the Assessment

Start by understanding where you are on your flourishing journey:

1. Open `assessment.html` in your browser
2. Answer questions across all 8 dimensions
3. Get personalized agent recommendations based on your results
4. Connect with and contribute to the community (push those belonging and transcendence scores up)
5. Repeat the assessment to see how you have progressed (up to you how frequent but I would recommend monthly or quarterly)

### Use an Agent

```bash
# Clone the repository
git clone https://github.com/openflourish/openflourish.git
cd openflourish

# Browse available agents
ls agents/

# Each agent has its own README with setup instructions
cd agents/sleep-optimizer
cat README.md
```

### Create Your Own Agent

See [CONTRIBUTING.md](CONTRIBUTING.md) for detailed instructions on creating and submitting agents.

---

## Project Structure

```
openflourish/
├── README.md
├── CONTRIBUTING.md
├── CODE_OF_CONDUCT.md
├── LICENSE
├── assessment.html          # Interactive flourishing assessment
├── agents/                  # All community agents
│   ├── _template/          # Template for new agents
│   ├── physiological/      # 🫀 Basic needs agents
│   │   ├── sleep-optimizer/
│   │   ├── nutrition-tracker/
│   │   └── movement-reminder/
│   ├── safety/             # 🛡️ Security & stability agents
│   │   ├── budget-coach/
│   │   ├── career-advisor/
│   │   └── health-navigator/
│   ├── belonging/          # 💜 Connection agents
│   │   ├── relationship-coach/
│   │   ├── community-finder/
│   │   └── friendship-cultivator/
│   ├── esteem/             # ⭐ Self-worth agents
│   │   ├── confidence-builder/
│   │   ├── goal-tracker/
│   │   └── achievement-coach/
│   ├── cognitive/          # 🧠 Learning & growth agents
│   │   ├── curiosity-sparker/
│   │   ├── learning-curator/
│   │   └── brain-trainer/
│   ├── aesthetic/          # 🎨 Beauty & creativity agents
│   │   ├── creativity-coach/
│   │   ├── nature-scheduler/
│   │   └── space-organizer/
│   ├── actualization/      # 🌳 Self-actualization agents
│   │   ├── purpose-finder/
│   │   ├── growth-coach/
│   │   └── flow-optimizer/
│   └── transcendence/      # 🌟 Beyond-self agents
│       ├── service-matcher/
│       ├── legacy-planner/
│       └── gratitude-practice/
├── docs/                   # Documentation
│   ├── philosophy.md
│   ├── agent-guidelines.md
│   └── maslow-framework.md
└── web/                    # Web assets
    ├── index.html
    └── assessment.html
```

---

## The 8 Dimensions

Each dimension has multiple subsections. Agents can target specific subsections:

### 🫀 Physiological
| Subsection | Emoji | Focus |
|------------|-------|-------|
| Nutrition & Hydration | 🍎 | Eating well, staying hydrated |
| Sleep & Rest | 😴 | Quality sleep, recovery |
| Physical Activity | 🏃 | Movement, exercise, strength |
| Shelter & Environment | 🌡️ | Safe, comfortable living space |

### 🛡️ Safety
| Subsection | Emoji | Focus |
|------------|-------|-------|
| Physical Safety | 🏠 | Feeling secure from harm |
| Financial Security | 💰 | Income, savings, stability |
| Employment Stability | 💼 | Job security, career path |
| Health Security | 🏥 | Healthcare access, wellness |

### 💜 Love & Belonging
| Subsection | Emoji | Focus |
|------------|-------|-------|
| Family Connections | 👨‍👩‍👧‍👦 | Family relationships |
| Friendships | 👥 | Close friends, social bonds |
| Intimate Relationships | 💑 | Romantic, deep connections |
| Community & Groups | 🤝 | Belonging to communities |

### ⭐ Esteem
| Subsection | Emoji | Focus |
|------------|-------|-------|
| Achievement & Competence | 🏆 | Skills, accomplishments |
| Self-Respect & Confidence | 🪞 | Self-esteem, self-compassion |
| Recognition from Others | 👏 | Respect, appreciation |

### 🧠 Cognitive
| Subsection | Emoji | Focus |
|------------|-------|-------|
| Learning & Education | 📚 | Acquiring knowledge |
| Curiosity & Exploration | 🔍 | Wonder, discovery |
| Problem-Solving | 🧩 | Critical thinking, puzzles |

### 🎨 Aesthetic
| Subsection | Emoji | Focus |
|------------|-------|-------|
| Nature & Natural Beauty | 🌸 | Time outdoors, appreciation |
| Art & Creative Expression | 🖼️ | Creating, appreciating art |
| Order, Harmony & Design | ✨ | Beautiful environments |

### 🌳 Self-Actualization
| Subsection | Emoji | Focus |
|------------|-------|-------|
| Purpose & Meaning | 🎯 | Life direction, values |
| Personal Growth | 🌱 | Becoming better |
| Authenticity | 💫 | Being true to yourself |
| Peak Experiences & Flow | 🔥 | Deep fulfillment, flow states |

### 🌟 Transcendence
| Subsection | Emoji | Focus |
|------------|-------|-------|
| Spirituality & Greater Meaning | 🙏 | Connection to something larger |
| Service & Altruism | 💝 | Helping others |
| Legacy & Contribution | 🌍 | Impact beyond yourself |
| Unity & Interconnection | 🕊️ | Oneness, compassion |

---

## Contributing

We welcome contributions from everyone! See [CONTRIBUTING.md](CONTRIBUTING.md) for:

- How to create a new agent
- Code standards and guidelines
- How to submit a pull request
- Community guidelines

### Ways to Contribute

- 🤖 **Create an agent** - Build a new agent for any subsection
- 📝 **Improve docs** - Help others understand the project
- 🐛 **Report bugs** - Found an issue? Let us know
- 💡 **Suggest ideas** - Share your vision for human flourishing
- ⬆️ **Upvote agents** - Star and recommend helpful agents
- 🌍 **Translate** - Help make OpenFlourish accessible globally

---

## Agent Upvoting & Community

### How Upvoting Works

Each agent directory contains a `metadata.json` with community metrics:

```json
{
  "name": "sleep-optimizer",
  "stars": 142,
  "reviews": 28,
  "average_rating": 4.7
}
```

Users can:
- ⭐ **Star** agents they find helpful
- 📝 **Review** agents with feedback
- 🏆 **Badges** are awarded to top-rated agents

### Community Discussions

Join the conversation:
- [GitHub Discussions](https://github.com/openflourish/openflourish/discussions) - Ask questions, share ideas
- [Agent Showcase](https://github.com/openflourish/openflourish/discussions/categories/agent-showcase) - Share your agents
- [Success Stories](https://github.com/openflourish/openflourish/discussions/categories/success-stories) - How OpenFlourish helped you

---

## Philosophy

OpenFlourish is built on these principles:

1. **Human-Centered AI** - Technology should serve human flourishing, not just efficiency
2. **Open & Accessible** - Free, open source, available to everyone
3. **Community-Driven** - Built by people who care about human well-being
4. **Evidence-Informed** - Grounded in psychology and well-being research
5. **Holistic** - Addressing all dimensions of human needs

Read more in [docs/philosophy.md](docs/philosophy.md).

---

## License

This project is licensed under the MIT License - see [LICENSE](LICENSE) for details.

---

## Acknowledgments

- Abraham Maslow's hierarchy of needs framework
- The positive psychology and well-being research community
- All contributors who believe in human flourishing

---

<p align="center">
  <strong>From Foundation to Flourishing</strong><br>
  <sub>Built with 💜 by the OpenFlourish community</sub>
</p>
