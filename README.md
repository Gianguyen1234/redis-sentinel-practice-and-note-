# redis-sentinel-practice-and-note-
repo chứa tài liệu dành cho ai muốn tìm hiểu về redis sentinel

<img width="610" height="410" alt="image" src="https://github.com/user-attachments/assets/251d7a12-979c-4e6d-afb5-d56ca435de1a" />
<img width="1024" height="615" alt="image" src="https://github.com/user-attachments/assets/d7af8712-4406-40de-9485-9745cdb831ef" />


# Tài liệu chi tiết để học redis sentinel
- Đây là trang mà mình thấy họ nói rất rõ về redis sentinel (mặc dù là bằng tiếng anh nhưng nó rất dễ hiểu): https://redis-doc-test.readthedocs.io/en/latest/topics/sentinel-old/
- Trang tài liệu chính thức trên redis: [High availability with Redis Sentinel](https://redis.io/docs/latest/operate/oss_and_stack/management/sentinel/)
- file pdf Configuring Redis High Availability Using Sentinels: https://cloud.samsungsds.com/serviceportal/sub/assets/pdf/en/SDS_Technical_Guide_Configuring_Redis_to_be_high_availability_using_Sentinels_v1_en.pdf

# Redis sentinel practice on VM
[Redis Sentinel – Practice trên VM](../../wiki/Redis-sentinel-practices-on-VM)

# Redis sentinel common mistakes
## 1: Redis Sentinel – Lỗi Trùng Myid Khi Copy Config ( đây là 1 trong những lỗi khác các sentinel ko thể giao tiếp và biết đến nhau do sự trùng lặp myid)
 **Bài viết chi tiết**:  
[Redis Sentinel – Lỗi trùng myid khi copy config](../../wiki/Redis-Sentinel-%E2%80%93-L%E1%BB%97i-Tr%C3%B9ng-Myid-Khi-Copy-Config)
