# docker_build('livinglikelarry', './texas')
# docker_build('isitthepie', './texas-ui')

k8s_yaml('livinglikelarry-deployment.yml')
k8s_yaml('isitthepie-deployment.yml')

# k8s_resource(
#     new_name='microservices',
#     workload='microservice1-deployment',
#     port_forwards=[
#             port_forward(3000, 3000, "app"),
#         ]
#     )

# k8s_resource(new_name='microservices', workload='microservice2-deployment', port_forwards=4200)

# k8s_resource('deployment', 'livinglikelarry', 'livinglikelarry-deployment')
# k8s_resource('deployment', 'isitthepie', 'isitthepie-deploymentml')