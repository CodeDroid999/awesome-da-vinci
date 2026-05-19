
# The Last Supper as Event-Sourced Architecture

## Reality Recorded as Immutable Events

Under traditional interpretation, :contentReference[oaicite:0]{index=0} represents a singular historical scene.

Under software architecture interpretation, it functions as an **event-sourced system**, where all meaning is derived not from current state, but from a complete log of immutable events.

The painting is not a snapshot.

It is an event log rendered as human experience.

---

# Core Principle of Event Sourcing

In event sourcing:

- state is not stored directly
- only events are stored
- current state is reconstructed by replaying events in order

Applied to the painting:
- “betrayal will occur” is not a state
- it is an event appended to history
- all reactions are downstream projections of that event

The system does not show “what is.”

It shows “what happened, and what it caused.”

---

# The Event Stream Begins

The system contains a single high-impact domain event:
