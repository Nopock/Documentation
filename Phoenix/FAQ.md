<details>
<summary>How can I set up ranks?</summary>

You can set up ranks by using the `/rank` command. Be sure to go to Phoenix `bukkit.yml` config and locate the phoenix operators part in the config and add your UUID for you can have access to rank management commands. You can create a command by doing `/rank create` and then editing it in `/rank editor` or you can use the provided commands to edit it manually by doing `/rank [command]`
</details>
  
<details>
<summary>My menus are not working on 1.12+ servers.</summary>

To ensure your menus work properly on 1.12+ servers, follow these steps:

1. Go to guiconfig.yml file.
2. Locate the "fill-glass" section.
3. Change the material to something like "GRAY_STAINED_GLASS_PANE" under "fill-glass".
4. Save and restart your server.
</details>
  
<details>
<summary>I have an error saying Missing Dependency. Why am I getting this?</summary>

A: This usually means you are missing a dependency such as PlaceholderAPI!
</details>
  
<details>
<summary>Why can’t I grant when I am OP??</summary>

A: Please ensure you have core.grant.* or core.grant.rankName AND you are above the rank you are trying to both !
</details>
  
<details>
<summary>Why am I being blacklisted randomly when I op someone or I get opped!?</summary>

This is because of our security system we added. Please do security add [ign] or disable it in the config.
</details>
  
<details>
<summary>Why is Tab broken?</summary>

A: Some versions are not supported yet.
</details>
  
<details>
<summary>How do I grant a rank from console?</summary>

You can grant a rank from the console using the `/ogrant` command
</details>
  
<details>
<summary>How do I add a tag to a rank?</summary>

Add the permission autotaggrant.tagName or .* to the rank
</details>