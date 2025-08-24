# Vibe Coding for PMs 🚀

A comprehensive template system designed to help Product Managers transform ideas into working code through structured AI collaboration and systematic development workflows.

## 🎯 What This Is

This template provides Product Managers with a structured approach to:
- **Ideate & Spec**: Transform rough ideas into detailed technical specifications
- **Plan & Architect**: Break down projects into manageable development phases
- **Build & Iterate**: Guide AI developers through systematic implementation
- **Review & Refine**: Ensure quality and maintainability of delivered code

## 🏗️ Core Architecture

### Context Architecture (`context-architecture/`)

The foundation of your project thinking and decision-making process:

#### Project Structure Template
```
your-project/
├── @Core-foundation/
│   ├── product-vision-strategy.md
│   ├── how-i-work.md
│   └── technical-architecture.md
├── Active-hypotheses/
├── Decision-contexts-log/
├── Evidence-repository/
└── README.md
```

**Key Principles:**
- **Use folder structure as thinking structure** - Organize your thoughts through systematic file organization
- **Create templates** for hypotheses, decision logs, and other recurring documentation needs
- **Document AI conversations** to maintain context and track decision rationale

#### Core Foundation Components
- **`product-vision-strategy.md`** - Define your product's north star and strategic direction
- **`how-i-work.md`** - Document your working style, preferences, and collaboration patterns
- **`technical-architecture.md`** - Outline the technical foundation and constraints

#### Active Development Areas
- **`Active-hypotheses/`** - Track current assumptions and testable ideas
- **`Decision-contexts-log/`** - Record key decisions with context and rationale
- **`Evidence-repository/`** - Store research, user feedback, and supporting data

### Prompt Templates (`prompt-templates/`)

Systematic AI collaboration patterns for each phase of development:

#### 1. **Hone the Idea** (`hone-the-idea.md`)
Transform rough concepts into detailed specifications through iterative questioning:
- Guides you through creating a minimum viable specification
- Asks focused questions one at a time to deepen understanding
- Exports final spec to `spec.md`
- Optionally initializes GitHub repository

**When to use:** At the very beginning when you have a concept but need to flesh it out

#### 2. **Plan the Prompt** (`plan-the-prompt.md`)
Convert specifications into actionable development plans:
- Creates detailed technical implementation plans
- Breaks projects into logical development phases
- Generates developer prompts for each technical milestone
- Outputs `plan.md` and `todo.md` for tracking

**When to use:** After you have a spec and need to create a development roadmap

#### 3. **Do the Plan** (`do-the-plan.md`)
Execute your development plan systematically:
- Reviews pending prompts and implements them one by one
- Ensures tests pass and builds succeed
- Commits work with descriptive messages
- Marks prompts as completed
- Pauses for validation after each implementation

**When to use:** When you're ready to start building and have a plan in place

#### 4. **Review** (`review.md`)
Quality assurance and code review:
- Conducts thorough code review of implemented features
- Identifies potential bugs, edge cases, and inconsistencies
- Ensures code quality and maintainability

**When to use:** After each major implementation phase or before final delivery

## 🔄 Workflow Integration

### Design-to-Code Workflow (`workflows/design-to-code.md`)
Seamlessly integrate Figma designs into your development process:
1. Enable MCP in Figma
2. Configure AI IDE with Figma MCP settings
3. Use Figma variables for component transformation
4. Copy Figma selection links directly into your development workflow

### PM Code Review Workflow (`workflows/pm-code-review.md`)
Systematic approach to code reviews from a product perspective:
1. **Structured Checklist** - Cover business logic, UX, data integrity, and quality standards
2. **Guiding Questions** - Specific questions to ask during each review category



## 🚀 Getting Started

### 1. **Initialize Your Project**
```bash
# Clone this template
git clone <your-template-repo>
cd vibe-coding-for-pms

# Customize the context-architecture for your project
# Start with product-vision-strategy.md
```

### 2. **Define Your Foundation**
- Fill out `context-architecture/product-vision-strategy.md`
- Document your working style in `context-architecture/how-i-work.md`
- Outline technical constraints in `context-architecture/technical-architecture.md`

### 3. **Start with an Idea**
Use the `prompt-templates/hone-the-idea.md` template:
```markdown
Here is the idea: [Your concept here]
```

### 4. **Plan Your Implementation**
Use the `prompt-templates/plan-the-prompt.md` template with your spec to create a development roadmap.

### 5. **Execute Systematically**
Use the `prompt-templates/do-the-plan.md` template to guide AI developers through implementation.

## 💡 Best Practices

### For Context Architecture
- **Keep it current** - Update your foundation documents as your understanding evolves
- **Use consistent naming** - Establish clear conventions for files and folders
- **Link related concepts** - Create cross-references between related documents

### For Prompt Templates
- **Follow the sequence** - Use templates in order: Hone → Plan → Do → Review
- **Customize thoughtfully** - Adapt templates to your specific project needs
- **Document decisions** - Use your decision log to track why you chose certain approaches

### For AI Collaboration
- **Be specific** - Provide clear context and constraints
- **Iterate systematically** - Use the review template to catch issues early
- **Maintain context** - Reference your foundation documents in AI conversations

### For Code Reviews
- **Use the structured checklist** - Follow the PM code review workflow systematically
- **Focus on business impact** - Prioritize issues that affect user experience and business logic

## 🔧 Customization

This template is designed to be adapted to your specific needs:

- **Modify folder structures** in `context-architecture/` to match your thinking patterns
- **Extend prompt templates** with project-specific requirements and constraints
- **Add new workflows** for specialized development processes
- **Integrate with your tools** - MCP configs are provided for filesystem, Linear, and memory management

## 📚 Template Philosophy

This system is built on the principle that **structure enables creativity**. By providing systematic approaches to:

- **Idea development** (Hone the Idea)
- **Technical planning** (Plan the Prompt)
- **Systematic execution** (Do the Plan)
- **Quality assurance** (Review)

You can focus on the creative and strategic aspects of product development while ensuring technical implementation follows solid engineering practices.

## 🤝 Contributing

This template evolves based on real-world usage. Share your adaptations and improvements to help other PMs succeed with vibe coding.
