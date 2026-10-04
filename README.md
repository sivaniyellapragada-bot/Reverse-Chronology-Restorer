# Reverse-Chronology-Restorer
A Python and Pandas based project to restore a 10,000+ row IoT temperature sensor CSV from reverse chronological order to correct the oldest-first order, following memory and verification constraints.
## Abstract
The increasing use of Internet of Thungs(IoT) devices has resulted in the continous generation of large volumes of sensor data including temperature measurements recorded at regular time intervals.
Maintaining the correct chronological order of such data is essential for accurate analysis, visualization, and interpretation of time-series information.
However, sensor datasets may sometimes be stored or received in reverse chronological order,requiring reliable restoration before further processing.
This project, Reverse- Chronology-Restorer focuses on restoring a 10,000+ row to IoT temperature sensor dataset from reverse chronological order to the correct olderst-first sequence using Python and Pandas.
The implementation is designed with the emphasis on data integrity,memory-concious processing, and systematic verification.
Timestamp information is processed to establish the required chronological sequence while preserving the associated sensor measurements and original dataset structure.
To ensure the reliability of the restoration process, mutliple verification checks are incorporated, including row- count validation, column integrity, timestamp ordering, and consistency between the original and restored records.
The resulting dataset is stored as a separate output file,allowing the original data to remain unchanged.
The oroject demostrates the physical application of python-based data processing techniques for restoring and validating time-series sensor data.
It also provides a structured approach to handling large CSV datasets while emphasizing correctness, reproducibility, and data integrity.
## Introduction
The rapid growth of Internet of Things (IoT) technology has led to the generation of large volumes of sensor data from connected devices.
Temperature sensors are widely used in applications such as environmental monitoring, industrial systems
