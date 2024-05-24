### almushel.h

```c
typedef struct developer {
	char* name;
	char* languages[4];
	char* interests[5];
	char* other[3];
} developer;

static developer almushel = {
	.name = "Andrew Mushel",
	.languages = { "C", "Go", "JavaScript :(", "Python :[" },
	.interests = { "Gameplay", "Game Engines", "Systems", "Graphics", "Web :|" },
	.other = { "Technical Writing", "Sound Design", "Music" }
};
```

