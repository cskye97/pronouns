%pronouns package

%provides randomly chosen pronoun sets for maximum

%chaos in your gender-neutral writing

%inspired by the therefor package at https://github.com/bgschiller/latex-therefore

%requires arrayjobx and lcg

%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%

%% Use                                           %%

%% Write as if you were using singular they,     %%

%% replacing it with appropriate LaTeX commands, %%

%% for instance \They, \themself. Verbs can be   %%

%% conjugated with \s, \es, \are, \were, \re, and%%

%% \have. Optionally pass a number (1-5; default %%

%% is 1) to refer to different people (but it is %%

%% not guaranteed that the randomly chosen       %%

%% pronouns are different): \They[1] see \them[2]%%

%% Pay attention to how LaTeX handles spacing    %%

%% after commands: \They\ see something.         %%

%% Also pay attention to capitalization; you may %%

%% need to use other commands to get i.e. THEY.  %%

%% Use \set to initialize and whenever you want  %%

%% to change pronouns.                           %%

%% Options:                                      %%

%% noplural prevents the package from using      %%

%%  `they,' allowing you to ignore conjugations. %%

%% restrict sets the pronoun set to only they,   %%

%%  she, and he (or she and he with noplural)    %%

%% seed=XXXX sets the random seed used by lcg    %%

%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
