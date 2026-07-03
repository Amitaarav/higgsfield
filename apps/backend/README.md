# backend

To install dependencies:

```bash
bun install
```

To run:

```bash
bun run index.ts
```

This project was created using `bun init` in bun v1.3.12. [Bun](https://bun.com) is a fast all-in-one JavaScript runtime.


Users
id              username                pass

Users Avatar    1:many

Avatar
id              userId                  name

Avata AvatarImage   1:many
AvataImage
id              avatarId                url

Users   AvatarVideo         1:many

AvatarVideo
id              prompt              startFrame          endFrame            duration            width           height

Avatar  avatarVideoRefernces        1:many
AvatarVideo     avatarReferences    1:many
AvatarVideoReferences
id                  avatarVideoId           avatarId