# Managing Teams and Channels

**Audience:** Department directors and anyone responsible for managing a YSE Team  
**Last updated:** June 2026

---

## How YSE Uses Teams

Each YSE department has its own **Team** (a shared workspace in Microsoft Teams). Department directors are the **owners** of their Team and are responsible for:

- Managing who is a member of the Team
- Creating, editing, and archiving channels within the Team
- Setting channel permissions

The IT admin manages the Teams tenant itself (creating and deleting Teams, assigning licenses) but does **not** manage the day-to-day membership or channel structure within each department's Team. That is your responsibility as a director.

!!! info "Need a new Team created?"
    Only IT admins can create or delete a Team. If your department needs a new Team, or an existing Team needs to be deleted, contact **support@youthsecurity.org**.

---

## Understanding the Structure

| Concept | What it is |
|---|---|
| **Team** | The top-level workspace for your department. Contains all members and channels. |
| **Channel** | A topic-based space within a Team for focused conversations and files. |
| **Standard channel** | Visible and accessible to all members of the Team. |
| **Private channel** | Visible only to specific members you invite; useful for sensitive sub-groups within the Team. |
| **Owner** | A Team member with management rights: can add/remove members, create/delete channels, change settings. |
| **Member** | A Team member with access to all standard channels. Can post and interact but cannot manage the Team. |

---

## Managing Team Membership

### Add a member to your Team

1. In the left sidebar, click **Teams** and find your department's Team.
2. Click the **`...`** (More options) next to the Team name.
3. Select **Manage team**.
4. Click **Add member**.
5. Search for the person by name or YSE email address and select them.
6. Choose their role (**Member** or **Owner**) and click **Add**.

!!! tip "Owners can manage the Team; members cannot."
    Only assign the Owner role to people who should be able to add/remove others and manage channels. For most colleagues, Member is the right choice.

### Remove a member from your Team

1. Go to **Manage team** (as above).
2. Click the **Members** tab.
3. Find the person in the list and click the **✕** to the right of their name.
4. Confirm the removal.

!!! note "Removing someone from the Team removes their access to all standard channels immediately."
    Private channels have their own membership; if the person is also in a private channel, remove them there separately (see [Managing Private Channels](#private-channels) below).

### Change a member's role

1. Go to **Manage team → Members**.
2. Click the dropdown next to the person's name (showing **Member** or **Owner**).
3. Select the new role.

---

## Managing Channels

### Create a new channel

1. Click **`...`** next to your Team name and select **Add channel**.
2. Give the channel a clear, descriptive name.
3. Add an optional description to help members understand its purpose.
4. Choose the channel type:
   - **Standard**: visible to all Team members
   - **Private**: visible only to the members you specify
5. Click **Create**.

!!! tip "Name channels for their purpose, not their audience."
    A channel named `#grant-applications` is clearer than `#directors-only`. Good names make the workspace self-explanatory to new members.

### Edit a channel name or description

1. Click **`...`** next to the channel name.
2. Select **Edit channel**.
3. Update the name or description and click **Save**.

### Delete a channel

1. Click **`...`** next to the channel name.
2. Select **Delete channel**.
3. Confirm the deletion.

!!! warning "Deleting a channel permanently removes all its messages and files."
    This action cannot be undone. If you want to preserve the content, consider archiving the files to SharePoint first, or simply leaving the channel in place and posting a notice that it is no longer in use.

### Reorder channels

Click and drag any channel in the list to reorder it. The **General** channel is pinned at the top and cannot be moved or deleted.

---

## Private Channels

Private channels are useful when a subset of your Team needs a space for sensitive discussions (for example, a directors-only channel within a broader departmental Team).

### Create a private channel

Follow the steps under [Create a new channel](#create-a-new-channel) and select **Private** as the channel type. You will be prompted to add the initial members immediately.

### Manage private channel membership

Private channels have their own membership list, separate from the main Team.

1. Click **`...`** next to the private channel name.
2. Select **Manage channel**.
3. Use **Add member** to add people, or click **✕** to remove them.

!!! note "Only members of the Team can be added to a private channel within it."
    If someone is not yet in the Team, add them to the Team first (as a Member), then add them to the private channel.

---

## Best Practices for Directors

**Keep membership current.** When someone leaves your department or YSE, remove them from the Team promptly. This revokes their access to all files and conversations in the Team's channels.

**Use channels deliberately.** A Team with dozens of channels becomes hard to navigate. Start with a few well-named channels and create more only as a genuine need arises. A good default structure for most departments:

| Channel | Purpose |
|---|---|
| **General** | Announcements and topics that don't belong elsewhere (created automatically) |
| **#projects** or topic-specific channels | Active work and coordination |
| **#resources** | Shared documents, guides, reference material |

**Keep the General channel for announcements.** You can configure General so that only owners can post, making it a clean broadcast channel. Go to **`...` → Manage channel → Permissions** and set **"Who can post"** to **Owners only**.

**Archive rather than delete.** If a project or working group concludes, deleting its channel removes history. Instead, rename it with a prefix like `[archive]` and note in the description that it is no longer active, so the history stays accessible for reference.

---

## What Directors Cannot Do

Some actions require IT admin intervention. Contact **support@youthsecurity.org** for:

- Creating or deleting a Team entirely
- Changing the Team's name or external visibility settings
- Adding someone who does not yet have a YSE Microsoft 365 account (the account must be provisioned first)
- Recovering a deleted channel or Team

---

*See also: [Getting Started with Microsoft Teams](teams-guide.md) · [Logging In to Microsoft Teams](teams-login.md)*
