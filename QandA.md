# kuromi's Q and A

# Question: what does kuromi do?
- A: kuromi is a multipurpose discord bot designed to provide anti-nuke protection and offer various utility features to enhance your server's experience.

# Question: how do I configure kuromi's anti-nuke settings?
- A: you can do so by executing the command `;antinuke settings`, but you must execute the command: `;antinuke setup` in order to do so.

# Question: does kuromi have an open source code?
- A: no. 

# does kuromi save my data?
- A: yes but its not for the reason you think. we store your data such as: `user ids, server ids, and message content.` and this data is only visable to the **bot owner**

# Question: does kuromi have any other commands besides anti-nuke commands?
- A: yes, there are multiple commands not related to `anti-nuke`, you can view the commands by using `;help`

# Question: why didn't kuromi protect my server when it got nuked?
- A: there are multiple possibility's on why this happened.
- 1. **Role Hierarchy**: make sure kuromi's role `(kuromi)` has the necessary permissions and a role with a higher position in the role hierarchy than the potential nuker. if the nuker has a higher role or administrator permissions, they can bypass certain restrictions.
  2. **Whitelisted Users**: check your server's whitelisted users list. kuromi may allow actions from whitelisted users, so ensure that no unauthorized users are on this list.
  3. **Anti-Nuke module Disabled**: ensure that kuromi's anti-nuke module is enabled and actively monitoring your server. you can use the `;antinuke on` command to enable it if it's not already.
