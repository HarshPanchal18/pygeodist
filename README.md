# [pygeodist](https://pypi.org/project/pygeodist/0.0.1/)

## Description

* `pygeodist` is a lightweight and efficient library that provides functions to calculate the distance between two geographical points using their latitude and longitude coordinates.
* It utilizes the [Haversine formula](https://www.movable-type.co.uk/scripts/latlong.html) to accurately compute distances on the Earth's surface.

[![License](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)

## Installation

You can include the library in your project using one of the following methods:

```bash
pip install pygeodist
```

## Usage

```python
from geodistance.point import Point
from geodistance.main import calculate_distance

point1 = Point(41.19,65.85)
point2 = Point(29.19,16.85)
print(calculate_distance(point1,point2))

point1 = Point(3,3)
point2 = Point(6,12)
print(calculate_distance(point1,point2, "m"))
```

## Contributing

* Contributions are welcome! If you find any issues or have suggestions for improvements, please feel free to open an issue or submit a pull request. For major changes, it is recommended to first open a discussion to discuss the proposed changes.

## License

* This library is distributed under the MIT License. See the LICENSE file for more information.

## Contact

* For any questions or inquiries, please contact at [@HarshPanchal18](https://github.com/HarshPanchal18)

* Feel free to customize and expand this template to provide more details about your library and its functionalities.
