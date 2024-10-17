FROM chatwoot/chatwoot:latest
ENTRYPOINT docker/entrypoints/rails.sh
CMD ['bundle', 'exec', 'sidekiq', '-C', 'config/sidekiq.yml']