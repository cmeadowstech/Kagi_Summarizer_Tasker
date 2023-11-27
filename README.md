# Tasker solution for Kagi's Universal Summarizer

Let's you share from other apps to Kagi's Universal Sumarizer for quick and seamless summaries. Reliant on the AutoShare plugin for Tasker.

![image](https://github.com/cmeadowstech/Kagi_Summarizer_Tasker/assets/30964870/c1fc0c0f-4cc5-496b-a1cf-8e2bc9658d95)

## Installation

- You'll need to download and install the two .xml files. One as a scene, and one as a task.
  - task.xml - show_kagi_scene
  - scene.xml - kagi_scene
- You'll also need to set up an AutoShare profile that points to the show_kagi_scene task. I followed this Reddit thread - https://old.reddit.com/r/tasker/comments/94esb4/tutorial_creating_autoshare_commands_for_your/
- Once everything is configured, create a variable called %KAGI_TOKEN and populate it with session token from your [Kagi Account settings](https://kagi.com/settings?p=user_details). You only need the token after ?token=. 
