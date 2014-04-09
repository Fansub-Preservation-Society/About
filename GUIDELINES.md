Guidelines
==========

1. We do not accept subtitles from groups that do straight rips from
   Crunchyroll/FUNimation/Aniplex/etc. These subtitles are legally owned by these
   corporations & we wish to not wander into these legal "grey-areas".
2. We only accept .ass subtitles.
3. We do not include the font files necessary for these subtitles to visually fully work.
   We do encourage the a list of fonts used within the release of a series with links to
   legit sources to acquire the necessary font files.
4. Each repo name will be formatted as so:
>  * Solo group repos will have the complete name of the group per listed on
>    [AniDB.net](http://anidb.net).
>  * Joint group repos will have the short name of the group per listed on
>    [AniDB.net](http://anidb.net).
>  * Joint group repors will have "joint_" parsed in front of the name of the repo to
>    make it easier to identify as a joint group repo.
>  * The name of the group will be use periods as substitution for spaces.
>  * The repo name will end with a dash followed by the three character ISO 639-2 code
>    for the language of the releaes. If a group releases in multiple languages, there
>    will be a repo for each language.
5. Within each repo, all the releases will sorted by the official romaji name of the anime
   per listed on [AniDB.net](http://anidb.net).
6. The file name of each subtitle file will be formated as follows:
>  * The file name will start with a closed bracket with the release group's short name
>    per listed on [AniDB.net](http://anidb.net).
>  * The file name will continue with the complete romaji name of the anime per listed on
>    [AniDB.net](http://anidb.net). (Should match the directory name).
>  * The file name will then contain the number of the episode this is in the series,
>    using two digits if the series is under 100 episodes long & using three digits if
>    the series is 100 to 999 episodes long. If the subtitle file is from a movie
>    release, this can be ommitted.
>  * The file name will then be completed with the dimension this subtitle file is setup
>    for.
7. A submodule will be setup connecting joint repos to their "parent" fansub group repos.
   The submodule will go within a "joint" directory and the submodule will have the name
   of the corresponding joint group. For example, In the Vivid Subs repo there is a
   submodule in the "joint" directory called "Unlimited Translation Works" that connects
   to the UTW-Vivid joint repo.
