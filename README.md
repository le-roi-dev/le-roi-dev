## Hi, I'm Le Roi Dev. Full Stack Developer

```python
class Le_roi_dev:

    def __init__(self):
        self.username = 'Le-Roi-Dev'
        self.position = 'Full Stack Developer'
        self.code = {
            'backend': ['Python', 'Django', 'NodeJS', 'Laravel', 'Odoo', 'Flask', 'FastAPI'],
            'database': ['PostgreSQL', 'MySQL', 'SQLite3', 'Mongo DB', 'Redis'],
            'frontend': ['JavaScript', 'TypeScript', 'ReactJS', 'NextJs', 'Tailwind CSS', 'Boostrap', 'MUI'],
            'tools': ['GIT', 'GitHub', 'GitLab', 'Pandas', 'Jupyter notebook', 'SQLAlchemy', 'Celery', 'Nginx'],
            'misc': ['Firebase', 'TDD', 'SCRUM', 'SOLID', 'gRPC', 'ML', 'Tech Writer']
            'devops': ['Docker', 'Linux', 'Jenkins', 'GitHub Actions', 'AWS', 'Proxmox'],
        }
        self.architecture = ['SPA', 'MVC', 'Serverless', 'microservices']

    def __str__(self):
        return f'{self.name} | {self.position}'

if __name__ == '__main__':
    me = Le_roi_dev()
    print(me)

```
