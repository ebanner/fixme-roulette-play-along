# 🛝 fixme-roulette-play-along

## Clone code

```bash
$ git clone https://github.com/SerenityOS/serenity.git irq
```

## Find commit

```bash
$ time git log -S "FIXME: This is a HACK" --pretty=format:"%h - %an, %ar : %s" -- Userland/Libraries/LibC/pwd.cpp
```

http://github.com/SerenityOS/serenity/commit/<commit-hash>

Click "parent" commit

Copy commit hash

Put hash in notion

```bash
$ git checkout <hash>
```

## Setup code

```bash
./install.sh fixme-irq
```

VSCode open folder

Verify FIXME is there

```bash
$ Meta/serenity.sh rebuild-toolchain
$ Meta/serenity.sh run
```

# View git blame in GitHub

https://github.com/SerenityOS/serenity/tree/<hash>
