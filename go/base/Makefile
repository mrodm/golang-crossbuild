include ../Makefile.common

ifeq ($(DOCKER_MULTIARCH),1)
DOCKER_CMD := $(SELF_DIR)/../.ci/scripts/buildx.sh

push:
	@echo "Already done by buildx (.ci/scripts/buildx.sh)."
atomic-push:
	@echo "Already done by buildx (.ci/scripts/buildx.sh)."
endif

ifeq ($(BUILDX)$(DEBIAN_VERSION),19)
DOCKER_CMD := $(SELF_DIR)/../.ci/scripts/buildx.sh

push:
	@echo "Already done by buildx (.ci/scripts/buildx.sh)."
atomic-push:
	@echo "Already done by buildx (.ci/scripts/buildx.sh)."
endif
