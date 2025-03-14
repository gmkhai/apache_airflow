# INTRODUCION
Airflow is orchecstration for Data pipline with complexity process. Airflow using DAG (Direct Acyclic Graph) Algorithm graph where ech node dependencies with another node, each node not cucle process. In DAGs have tasks, each task can did with operator. In this repositories I will make base of docker container. You can using this repositories for create your simple project. I will make this repositories with dynamic mecanism you can adjust with your needs.

# How to Install this Repositories
1. You can download or clone this repositories
2. Create python virtual environment for isolate with global environment using command `python -m venv venv`
3. Enter your python virtual environment using command `.\venv\Scripts\activate` or `source venv/bin/activate`
4. Run this command `pip install -r requirements.txt` in current position repositories for install all library python for running airflow
5. Make new folder using command `mkdir -p ./dags ./logs ./plugins ./config` this folder `dags` for create job/dags, `logs` for log each dag process, `plugins` for each all plugins using in airflow, `configs` configuration for running airflow
6.  Type this command for create, and running container `docker-compose -f docker-compose.yaml --env-file .env up -d`