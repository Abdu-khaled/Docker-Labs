
FROM ubuntu:latest


ENV SLEEP_DURATION=15


CMD ["sh", "-c", "echo 'Sleeping for ${SLEEP_DURATION} seconds...' && sleep ${SLEEP_DURATION} && echo 'Done sleeping!'"]



# Scenario 1:
# docker run ubuntu-sleep-enhanced


# Scenario 2:
# docker run -e SLEEP_DURATION=30 ubuntu-sleep-enhanced
