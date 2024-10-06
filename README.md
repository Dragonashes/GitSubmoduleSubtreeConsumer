# GitSubmoduleSubtreeConsumer

## Dependencies

### Git Subtree

#### Add subtree

git subtree add --prefix  home/subtreeDirectory https://github.com/Dragonashes/GitSubmoduleSubtree.git main --squash

#### Update subtree

git subtree pull --prefix home/subtreeDirectory https://github.com/Dragonashes/GitSubmoduleSubtree.git main --squash

### Submodules

#### Add submodule

git submodule add https://github.com/Dragonashes/GitSubmoduleSubtree.git ./home/submodules/submodule1
git submodule add https://github.com/Dragonashes/GitSubmoduleSubtree.git ./home/submodules/submodule2

#### Update submodule

git submodule update --init --recursive
