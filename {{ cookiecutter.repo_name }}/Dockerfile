FROM {{ cookiecutter.base_image }}

ENTRYPOINT ["echo", "Hello", "World!"]

LABEL io.whalebrew.name '{{ cookiecutter.name }}'
LABEL io.whalebrew.required_version '>0.3.0'

# LABEL io.whalebrew.config.environment '["TERM", "FOOBAR_NAME"]'
# LABEL io.whalebrew.config.keep_container_user 'true'
## Possible values are: 'error' | 'skip' | 'mount'
# LABEL io.whalebrew.config.missing_volumes 'error'
# LABEL io.whalebrew.config.networks '["host"]'
# LABEL io.whalebrew.config.ports '["8100:8100"]'
# LABEL io.whalebrew.config.volumes '["~/.docker:/root/.docker:ro"]'
# LABEL io.whalebrew.config.volumes_from_args '["-C", "--exec-path"]'
# LABEL io.whalebrew.config.working_dir '${PWD}'
