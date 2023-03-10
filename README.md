# Project Vision for Mobile Robotics Projects

|                         |                    |
| ----------------------- | ------------------ |
| Required Python Version | `3.9`              |

## Datasets

| Name           | URL                                                                                               |
| -------------- | ------------------------------------------------------------------------------------------------- |
| kitti05        | [kitti05](http://rpg.ifi.uzh.ch/docs/teaching/2021/kitti05.zip) (1.4 GB)                          |
| Malaga 07      | [malaga07](http://rpg.ifi.uzh.ch/docs/teaching/2021/malaga-urban-dataset-extract-07.zip) (4.4 GB) |
| Parking garage | [parking](http://rpg.ifi.uzh.ch/docs/teaching/2021/parking.zip) (208.3 MB)                        |

Download and extract to `/datasets`.


## Running the pipeline

1) Download the above datasets and extract them to `/datasets` with the directory names:
`kitti`, `malaga-urban-dataset-extract-07` and `parking`.
2) Choose the desired dataset in the `params.py` file.
3) Run `python main.py`.
4) Enjoy our VO pipeline :)

## Computer characteristics

- CPU frequency: 2.8 GHz
- RAM: 16GB
- Number of used threads: 1 for VO, 6 for VIO

## Video results

- Parking: https://www.youtube.com/watch?v=YZMLS5fn0GQ
- KITTI: https://www.youtube.com/watch?v=jE7d2QcfXvI
- Malaga: https://www.youtube.com/watch?v=UsEHJoqeqWo

