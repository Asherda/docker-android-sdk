FROM jangrewe/gitlab-ci-android

RUN curl -sL https://deb.nodesource.com/setup_8.x -o nodesource_setup.sh \
&& bash nodesource_setup.sh \
&& apt update \
&& apt install -y nodejs \
&& rm yarn-v$YARN_VERSION.tar.gz.asc yarn-v$YARN_VERSION.tar.gz \
&& curl https://install.meteor.com/ | sh -y
