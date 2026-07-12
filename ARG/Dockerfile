ARG version=8

FROM almalinux:${version}

ENV course="devops" \
    duration="120hrs"

ARG Trainer="shivakumar"

ENV Trainer=${Trainer}

RUN echo "Hi, course is: $course, duration is: $duration, Trainer is: $Trainer"

CMD ["sleep", "1000"]