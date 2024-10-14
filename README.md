# Golang pprof

```bash
curl http://localhost:3000/debug/pprof/heap > heap.out && \
go tool pprof -http=:8081 heap.out
```