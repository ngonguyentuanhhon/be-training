# Laravel Backend Roadmap

## 1. Foundation (bắt buộc)

### Git: github , gitlab, bibucket

-   init, clone
-   commit convention
-   branch
-   merge / rebase
-   stash
-   resolve conflict

### HTTP & Web basics (nắm basic về khái niệm)

-   request/response
-   headers
-   status code
-   cookie / session
-   authentication
-   RESTful API
-   CORS

### Basic Linux: (nâng cao)

-   file permission (`chmod`, `chown`)
-   process (`ps`, `kill`)
-   log (`tail -f`)
-   network (`netstat`, `curl`)
-   ssh
-   env variables


------------------------------------------------------------------------

## 2. Database

### SQL

-   CRUD
-   join
-   group by
-   subquery
-   aggregate

### Database design

-   normalization
-   one-to-one
-   one-to-many
-   many-to-many

### Advanced DB

-   index
-   transaction
-   locking
-   deadlock
-   query optimization
-   explain query
-   pagination

------------------------------------------------------------------------

## 3. PHP core

### Basic

-   OOP
-   namespace
-   trait
-   interface
-   abstract
-   static
-   dependency injection

### Advanced

-   composer
-   autoload PSR-4
-   exception handling
-   enum
-   match
-   attributes

------------------------------------------------------------------------

## 4. Laravel Core

### Basic flow: 

-   lifecycle request
-   route
-   controller
-   middleware
-   request validate
-   response
-   ...

> trong [laravel doc](https://laravel.com/docs/13.x) mục "The Basic" phải thành thạo được hết

### Database

-   migration
-   seeder
-   factory
-   query builder
-   Eloquent ORM
-   relationship
-   accessor / mutator / cast
-   scope

### Error handling

-   exception
-   custom exception
-   logging

### Auth

-   session auth
-   Jwt token

### Design patterns (nâng cao)

-   service layer
-   repository
-   factory
-   strategy
-   singleton
...

> Design patterns: chua cần ứng dụng luôn , sau khi thành thạo laravel rồi thì quay lại tìm hiểu và áp dụng , hiểu khai niệm và công dụng là được

------------------------------------------------------------------------

## 5. Async processing

### Queue / Job

-   dispatch
-   chain
-   batch
-   retry
-   failed job

### Event - Listener

-   sync / async event

### Scheduler

-   cronjob
-   task schedule

------------------------------------------------------------------------

## 6. Cache

-   cache concept
-   cache strategy
-   cache invalidation
-   rate limit
-   distributed cache

------------------------------------------------------------------------

## 7. Deployment & Infra

### Docker

-   Dockerfile
-   image
-   container
-   volume
-   network
-   docker compose

### Web server

-   Nginx
-   PHP-FPM

### Deploy stack

Laravel + Nginx + PHP-FPM + MySQL + Redis

------------------------------------------------------------------------

## 8. Message Queue (advanced)

-   Kafka / RabbitMQ
-   pub/sub
-   consumer
-   producer

> tech stack là với các dự án có sizing lớn hoặc build theo mô hình microserice thì sẽ chắc chắn phải dùng

> nên biết 1 trong 2 thằng cả 2 thì càng tôi, cty anh thì đang dùng kafka

------------------------------------------------------------------------

## 9. Testing

-   unit test
-   feature test
-   database test

> viết test thì chưa cần học luôn thành thạo laravel rồi quay lại học cũng được 


------------------------------------------------------------------------

## 10. Kubernetes (optional)

-   pod
-   deployment
-   service
-   configmap
-   secret
-   ingress

> cái này thực tế là job của devops, nhưng BE cũng nên nắm được khái niệm, cách hoạt động sau còn phối hợp với devops triển khai ứng dụng

------------------------------------------------------------------------

## 12. Frontend basic

-   HTML
-   CSS
-   JS
-   DOM
-   Ajax / Fetch
-   Blade
-   Form submit

------------------------------------------------------------------------

# Recommended learning order

Git → HTTP → SQL → PHP core → Laravel core → Queue → Cache → Docker →
Deploy → Testing → MQ → K8s
