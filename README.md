# data-set

This repository contains datasets and solutions related to WSRP-SCAL. The HVNS-SA with RS used to solve this problem is implemented and the results are stored in this repository.

## Directory Structure

- **data_set**: Contains the datasets used for the algorithm. Each dataset is represented by a `customer` and a `location` file.
  - The filenames follow the format `c-l-k`, where:
    - `c` is the number of customers.
    - `l` is the maximum number of designated locations for a customer.
    - `k` is the maximum number of service types.
  - Example: `C-5_1_1` and `L-5_1_1` represent customer and location files for the dataset `5-1-1`.

- **solution**: Contains the solutions for each dataset.
  - Each solution is stored in a text file named using the format `c-l-k`, corresponding to the dataset.
  - Example: `5-1-1` contains the solution for the dataset `5-1-1`.

## Dataset Format

### Customer File

The customer file contains information about the customers, their tasks, services, and task sequences.

- **CUST NO.**: Customer number.
- **TASK NUM.**: Number of tasks for the customer.
- **SERVICE TIME_1**: Service time of Task-Ⅰ.
- **TASK SEQUENCE**: Sequence number of the task.

### Location File

The location file contains information about the available service locations.



- **LOC NO.**: Location number.
- **CUST NO.**: Customer number.
- **XCOORD.**: X-coordinate of the location.
- **YCOORD.**: Y-coordinate of the location.
- **START TIME_1**: Start time of Task-Ⅰ.
- **DUE TIME_1**: Due time of Task-Ⅰ.

## Solution Format

Each solution is stored in a text file, and the format is as follows:

- **Instance**: Name of the instance.
- **Cost**: Total cost of the solution.
- **EMP**: Number of employees used in the solution.
- **DISTANCE**: Total distance traveled for the solution.
- **Solution**: Assignment of tasks and routes for each employee.








