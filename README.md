# Rust project template

Personal template to create rust projects using `cargo-generate`

How to use:
```
cargo generate --git https://github.com/jcvenegas/rust-template.git
cd <new-project>
./.ci/setup.sh
./.ci/.run.sh
git add .ci/ .github/ .gitignore .travis.yml
git commit -s
git remote add origin <your-repo>
git push origin master
```

License: Apache-2.0 OR MIT
