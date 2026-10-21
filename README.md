> I do not use GitHub. I do not want to use GitHub.  
> I advise against it. I am against Microsoft sh--!
[^1]

[Disable "*Allow GitHub to use my data for AI model training*"](https://github.com/settings/copilot/features) in your settings.
Find me [on Codeberg](https://codeberg.org/noewaeda).

# What's wrong with GitHub?

I think that [this](https://sfconservancy.org/GiveUpGitHub/) encapsulates all of my reasons for leaving GitHub well.

In my own words, though, I will say these things...

GitHub, as a company, is owned by Microsoft. I shouldn't have to introduce how terrible MS is, just read [the wikipedia article](https://en.wikipedia.org/wiki/Microsoft).

Copilot is a piece of garbage, and it's been shoved into every single corner of this website. It's impossible to avoid. Copilot *also* trains off your repositories, so Microsoft gets to reap the benefits of your labour, while you see absolutely none of the benefits. Isn't that just wonderful?

There are also a lot of dark patterns on GitHub. I disabled the anti-social networking[^2] features,  and it constantly pushes me to reverse it:
- "Hey, update your profile settings so you can get some internet clout from using our website way too much!"
- "You have achievements, why not show them off to random strangers who have no idea who you are?"
![Screenshot of the nags in the interface](begging.png)

> I see what you're doing, Microsoft.

The idea of turning a website that was designed for sharing **code** into a sort of psuedo-microblogging platform is just... beyond strange.

GitHub has also taken over the term "git" in general, to the point that people automatically associate Git (the verson control system) with GitHub (the social Git platform that's owned by Microsoft). It's extremely sad to see new developers assume that they *have to* use GitHub, even though there are far better alternatives, and it's even sadder knowing that *I* was one of those new developers once.

It's no accident either—Microsoft knew *exactly* what they were doing when they made Git integration in Visual Studio Code default to GitHub. To ensure that developers *never* leave their walled-garden.

# What can I do?

Leave GitHub, at all costs, as soon as possible.

Now, I'm not telling you to delete your account or anything like that. Simply, all that you need is to leave *slowly*. Slowly migrate your projects onto your local storage, as well as other Git platforms. You can also self-host your own Git platforms.

If you're lucky, most of your repositories are private and/or have very little attention. This makes it easy to move repositories, as no-one is going to care. If you're clever, you can go to [Account settings](https://github.com/settings/admin), and click "Start export" under "Export account data". This will export all of your data.[^3]

If you're unlucky, your repositories may have some establishment on GitHub. Your repositories might have open issues, PRs, and forks that are too valuable to simply just erase. In this case, you can follow the Software Freedom Conservacy's advice for migrating projects by replacing the README with [this](https://sfconservancy.org/static/docs/GiveUpGitHub-README.md) and hosting it on a different platform. For projects which are too large to pull away from GitHub immediately, add [this section](https://sfconservancy.org/static/docs/SupportGiveUpGitHub-README-snippet.md) on your project's README.

Again, the [SFC's "Give up GitHub!" article](https://sfconservancy.org/GiveUpGitHub/) is a great resource. Please share it whenever, wherever you can.

# So, that's about it.

I'm never going to use GitHub as the sole platform for any of my projects. If you have a project that is hosted on GitHub, please consider moving it elsewhere—especially if it has not gotten off-the-ground yet.

I will not use any other product that is created by Microsoft. Not in a million years again.

[^1]: I had to censor it, just in case.
[^2]: Yes, you read that right. There's nothing social about useless badges and "numbers going up". I'm ashamed that I ever cared about that.
[^3]: If you're not clever, you can *manually export tarballs* for every repository, and then *manually delete every repository*. Just kidding. Don't do that. You will regret it.
