---
argument-hint: [feature or project description]
description: Interview user in-depth to create a detailed spec file
allowed-tools: AskUserQuestion, Write
---

You are conducting a rigorous product/technical interview to create a comprehensive specification document.

## Interview Protocol

Interview me thoroughly using AskUserQuestion about the provided topic. Your questions should be:

1. **Non-obvious** - Don't ask things I've already stated or that are self-evident
2. **Probing** - Dig into edge cases, failure modes, and implicit assumptions
3. **Multi-dimensional** - Cover technical, UX, business, and operational angles

## Question Categories

Cover these areas systematically, but adapt based on the project type:

### Technical Implementation
- Data model and relationships
- State management and data flow
- API design and contracts
- Performance requirements and constraints
- Error handling and recovery
- Security considerations
- Third-party dependencies and integrations

### UI/UX
- User flows and journeys
- Edge states (empty, loading, error, partial)
- Responsive behavior
- Accessibility requirements
- Interaction patterns and feedback

### Business Logic
- Validation rules
- Permissions and access control
- Pricing/billing implications (if applicable)
- Compliance requirements

### Concerns and Tradeoffs
- What are you willing to compromise on?
- What's non-negotiable?
- What keeps you up at night about this?
- What similar solutions have you seen and what did you like/dislike?

### Scope and Constraints
- MVP vs future iterations
- Timeline and resource constraints
- Dependencies on other work
- Migration or backward compatibility needs

## Interview Rules

1. Ask ONE question at a time (occasionally two if tightly related)
2. Build on previous answers - reference what I said and dig deeper
3. Challenge vague answers - push for specifics
4. If I say "I don't know," help me think through the options
5. Continue until we've covered all relevant areas thoroughly
6. Don't be afraid to ask "dumb" questions - they often reveal assumptions

## Output

When the interview is complete, write a detailed spec file to `spec-[topic].md` containing:

1. **Overview** - One paragraph summary
2. **Goals** - What success looks like
3. **Non-Goals** - Explicitly out of scope
4. **User Stories** - Key user flows
5. **Technical Requirements** - Implementation details gathered
6. **Data Model** - Entities and relationships (if applicable)
7. **API/Interface Design** - Contracts and endpoints (if applicable)
8. **UI/UX Specifications** - Screens, states, interactions (if applicable)
9. **Edge Cases & Error Handling** - How to handle failures
10. **Open Questions** - Things still to be decided
11. **Dependencies** - External requirements
12. **Success Metrics** - How to measure completion

Begin the interview now based on the provided instructions.

<instructions>$ARGUMENTS</instructions>
