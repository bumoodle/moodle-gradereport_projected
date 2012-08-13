# Projected Final Grade

This report allows students to fill in unset gradebook values to obtain
a projected result of their final grade within the course.

## Features

- Allows automatic approximation of a student's grade in an asynchronous course using expected completion dates.
- Dynamic calls to calculate gradebook values
- Teachers can optionally disable feature
- _Must make_ feature gives students the ability to find out exactly what's
  required to achieve a certain letter grade in the course.

## Download

Visit [Projected's Github page][projected] to either download
a package or clone the git repository.

[projected]: https://github.com/lsuits/projected-final-grade

## Installation

To install Moodle 2.1+ using git, execute the following commands in the root of your Moodle install:

    git clone git://github.com/ktemkin/moodle-gradereport_projected.git grade/report/projected
    echo '/grade/report/projected' >> .git/info/exclude
    
Or, extract the following zip in your_moodle_root/report/grade:

    https://github.com/ktemkin/moodle-gradereport_projected/zipball/master


## Contributions

Contributions of any form are welcome. Github pull requests are preferred.

File any bugs, improvements, or feature requests in our [issue
tracker][issues].

[issues]: https://github.com/lsuits/projected-final-grade/issues

## License

Projected adopts the same license that Moodle does.
