
redis_cache: redis-server config/redis_cache.conf
redis_queue: redis-server config/redis_queue.conf

web: bench serve --port 8001

socketio: /home/kumkum/.nvm/versions/node/v20.16.0/bin/node apps/frappe/socketio.js


watch: bench watch


schedule: bench schedule

worker:  bench worker 1>> logs/worker.log 2>> logs/worker.error.log
worker-1:  bench worker 1>> logs/worker.log 2>> logs/worker.error.log
worker-2:  bench worker 1>> logs/worker.log 2>> logs/worker.error.log

