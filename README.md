# 🛝 fixme-roulette-play-along

## Clone code

% git clone https://github.com/SerenityOS/serenity.git irq

## Find commit

time git log -S "FIXME: This is a HACK" --pretty=format:"%h - %an, %ar : %s" -- Userland/Libraries/LibC/pwd.cpp

http://github.com/SerenityOS/serenity/commit/<commit-hash>

Click "parent" commit

Copy commit hash

Put hash in notion

$ git checkout <hash>

## Setup code

./install.sh fixme-irq

VSCode open folder

Verify FIXME is there

Meta/serenity.sh rebuild-toolchain

export CC=$(brew --prefix llvm)/bin/clang
export CXX=$(brew --prefix llvm)/bin/clang++

Meta/serenity.sh run

# View git blame in GitHub

https://github.com/SerenityOS/serenity/tree/<hash>
