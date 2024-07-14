# Todo-server
Todo API server application

| Method | Endpoint | 설명 |
| --- | --- | --- |
| GET | /tasks | 할 일 목록 조회 |
| POST | /tasks | 새로운 할 일 추가 |
| GET | /tasks/:id | 특정 할 일 조회 |
| PUT | /tasks/:id | 특정 할 일 수정 |
| PATCH | /tasks/:id/status | 특정 할 일의 상태 변경 |
| DELETE | /tasks/:id | 특정 할 일 삭제 |
| GET | /tasks?dueDate={dueDate} | 마감일별 할 일 목록 조회 |
| GET | /tasks/status/{status} | 상태별 할 일 목록 조회 |
| GET | /tasks/status | 할 일의 상태 목록 조회 |
