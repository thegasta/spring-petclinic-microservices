FROM egaillardon/jmeter-plugins:5.0.0-6.0.4

COPY ./petclinic_test_plan.jmx ./petclinic_test_plan.jmx

ENTRYPOINT ["jmeter", "-n", "-t", "petclinic_test_plan.jmx"]
