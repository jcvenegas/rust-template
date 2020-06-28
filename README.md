# Rust project template

Personal template to create rust projects using `cargo-generate`

How to use:
```sh
REPOSITORY="git@github.com:repo/repo.git"
cargo generate --git https://github.com/jcvenegas/rust-template.git
cd <new-project>
git remote add origin "${REPOSITORY}"
./.ci/setup.sh
./.ci/run.sh
git add .ci/ .github/ .gitignore .travis.yml *
git commit -s
git push origin master
```

License: Apache-2.0 OR MIT
