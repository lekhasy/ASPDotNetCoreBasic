# Mục tiêu

- Biết cách dùng EF Db First cơ bản
- Biết cách dùng 

# Cài đặt công cụ
- Docker
- Azure Data Studio hoặc SSMS - SQL Server Management Tool
- EF tool: dotnet tool install --global dotnet-ef

# Entity framework

1. setup:
- Giới thiệu EF - EF vs Dapper

2. practive:
- Thử tạo Db với EF code first
- Thử generate EF code từ Db vừa tạo (EF DB First)
- Dùng Secret Manager Tool để lưu connection string: 
    - dotnet user-secrets init
    - dotnet user-secrets set ConnectionStrings.BookStore '...'
- CRUD + Aggregate bằng EF
- Tối ưu hiệu suất EF

# Bài tập về nhà

- Thêm các field cần thiết cho Db
