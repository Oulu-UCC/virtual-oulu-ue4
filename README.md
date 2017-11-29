# 6aika-city

For a successful compilation clone repository with a different name (it must not start with a digit)!

Git LFS system, that used here might give errors when cloning. IF you face it, follow these steps:
```
// Skip smudge - We'll download binary files later in a faster batch
git lfs install --skip-smudge

// Do git clone here
git clone ...

// Go inside cloned directory and
// Fetch all the binary files in the new clone
git lfs pull

// Reinstate smudge
git lfs install --force
```