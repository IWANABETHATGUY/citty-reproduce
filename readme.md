# Citty will emit unhandled errors twice in `run` function

## Reproduce

1. `pnpm i`
2.  `node index.mjs hello`

**Actual**
![image](https://github.com/user-attachments/assets/e9b0255e-451a-4e5e-a7b1-2d4220ab1d70)


**Expected**
should only show errors once
