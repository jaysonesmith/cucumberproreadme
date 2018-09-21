# Tracking

This doc with document the project's settings and coordinating Cucumber Pro behavior.

## #1 - Basic, no features

*Note: This example's readme in the project root looks to be ignored moving forward in the Cutter (2018-07-19) release but I'm assuming it's not on master yet?*

### Project Structure

```
.
├── assets
├── features
├── README.md
└── TRACKING.md
```

### Cucumber Pro Output

![1](./assets/1.png)

## #2 - Single feature under /features

### Project Structure

```
.
├── assets
│  └── 1.png
├── features
│  └── test.feature
├── README.md
└── TRACKING.md
```

### Cucumber Pro Output

![2](./assets/2.png)

## #3 - Single feature under /features with matching README

### Project Structure

```
.
├── assets
│  ├── 1.png
│  └── 2.png
├── features
│  ├── README.md
│  └── test.feature
├── README.md
└── TRACKING.md
```

### Cucumber Pro Output

![3](./assets/3.png)