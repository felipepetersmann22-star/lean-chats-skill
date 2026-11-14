# Lean Chats

Carry the decisions, evidence and open work into the next stage of a project.

Use for a handover, a long conversation, a paused project, or resuming work. The skill preserves the existing workflow and does not assume a new chat or memory update is authorized.

## Install

Clone the repository into your agent's skills directory, keeping `SKILL.md` and its supporting files together. For Codex:

```sh
git clone https://github.com/felipepetersmann22-star/lean-chats-skill.git ~/.codex/skills/lean-chats
```

Refresh skill discovery if your agent requires it. Other agents may use a different directory. Review any skill before installing it.

## Example

For a project awaiting approval, note the pending decision and owner, link the relevant work, and continue independent tasks.

[Handover template](assets/handover-note.md) is included.

If no handover exists, reconstruct the essentials from available project records and recent relevant history, and label what you could not verify.

## Limits

This is a set of instructions, not a service. Results depend on the agent, available tools and task context; it cannot prove an action succeeded without checking the actual result.

## Source and license

This standalone repository began with the skill and its assets from the [original public agent-skills repository](https://github.com/felipepetersmann22-star/agent-skills/tree/1b7a3d8867363c0ff0dda0f9a117aacb7a16a347/skills/lean-chats), at commit `1b7a3d8867363c0ff0dda0f9a117aacb7a16a347`. See [CREDITS.md](CREDITS.md) and the [MIT license](LICENSE).
