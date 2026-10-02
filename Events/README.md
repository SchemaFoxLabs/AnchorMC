# Event archive

[Back to AnchorMC](../README.md)

## Usage for repository maintainers

1. Create an event record in `Events/YYYY-MM-DD-event-name.md`, using the event's import date and a descriptive file name.
2. Copy the event entry template below and replace its placeholders with verified values. The format is a documentation convention; store it in a `text` code block.
3. Record the publishing staff's public game identities, server identification, event description, rewards, scheduled time with time zone, and participant capacity. Add the actual participant count after the event.
4. Include organization metadata when applicable. Update the event count, partner history, and staff references as records change.
5. Add a relative link to the record under Archived events below, with its date and event name. Keep entries in reverse chronological order.

## Archived events

No event records have been added yet.

## Event entries

Choose one publishing role and one reward representation for each entry.

```text
Event:
[YYYY-MM-DD (Import Time)] <EventName> {
  permission: <Author | Staff | Moderator | Partner>

  release_staff:
    - IGN: <in-game name>
      UUID: <required Minecraft UUID>
      profile: <required public social media or GitHub profile URL>

  server: <internal identification>

  content:
    description: <event description>
    rewards: <list of strings OR list of objects>

  duration: [<timezone>] YYYY-MM-DD HH:mm ~ YYYY-MM-DD HH:mm
  player_capacity: <integer>
  player_actual: <integer>
}
```

Repeat the event block for additional events.

| Field | Meaning |
| :--- | :--- |
| Import Time | Date the entry was added to the log, using `YYYY-MM-DD`; distinct from the event's scheduled time. |
| EventName | The event's name. |
| `permission` | The publishing role: `Author`, `Staff`, `Moderator`, or `Partner`. This records a role; it does not grant access permissions. |
| `release_staff` | Staff responsible for publishing the entry. For each person, record the in-game name, required Minecraft UUID, and required public social media or GitHub profile URL. |
| `server` | The internal server identification from the README, such as `practice`. |
| `content.description` | A description of the event. |
| `content.rewards` | A list of reward descriptions, or a list of objects when attributes such as quantity or rarity are needed. |
| `duration` | Start and end date/time with an explicit time zone. Use 24-hour time and `YYYY-MM-DD HH:mm`; identify the zone with a name such as `Asia/Shanghai` or an explicit UTC offset. |
| `player_capacity` | Maximum number of participants, recorded as a nonnegative integer. |
| `player_actual` | Actual number of participants, recorded as a nonnegative integer. Do not invent a count before it is known. |

### Reward representations

Simple rewards can be a list of strings. Rewards with attributes can use objects.

```text
rewards:
  - <reward description>

OR

rewards:
  - name: <reward name>
    quantity: <integer>
    rarity: <rarity description, if applicable>
```

## Organization metadata

```text
OrganizationMeta {
  current_partner:
    - <current partner>

  history_partner:
    - <previous partner>

  event_quantity: <integer>

  stafflist:
    - IGN: <in-game name>
      UUID: <required Minecraft UUID>
      profile: <required public social media or GitHub profile URL>
}
```

- `current_partner`: current partners associated with the records.
- `history_partner`: previous partners associated with the records.
- `event_quantity`: total number of events represented by the associated records; keep it consistent when records are added or corrected.
- `stafflist`: staff entries with the same in-game name, required UUID, and required public profile information as `release_staff`.

Keep staff references to public game identities and public profile links. Do not add private contact details or real-world identifying information.
