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

## #4 - Nest feature under /features/test_directory_1 with README still under /features

This example is one in which I could see someone (like myself) setting up a project's landing page under /features and deciding to group features into directories for organization, especially with Pro's table of contents. 

Note that the table of contents does not reflect that the directory exists.

### Project Structure

```
.
├── assets
│  ├── 1.png
│  ├── 2.png
│  ├── 3.png
│  └── 4.png
├── features
│  ├── README.md
│  └── test_directory_1
│     └── test.feature
├── README.md
└── TRACKING.md
```

### Cucumber Pro Output

![4](./assets/4.png)

## #5 - Add nested readme to above project

This example is one that follows Pro's recommendation of putting a readme in the same nested directory as the feature. It unfortunately then ignores the landing page readme. The table of contents still does not show the directory that the feature is in.

### Project Structure

```
.
├── assets
│  ├── 1.png
│  ├── 2.png
│  ├── 3.png
│  └── 4.png
├── features
│  ├── README.md
│  └── test_directory_1
│     └── test.feature
├── README.md
└── TRACKING.md
```

### Cucumber Pro Output

![5](./assets/5.png)