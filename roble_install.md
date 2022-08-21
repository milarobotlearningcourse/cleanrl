# Setup code


1. `git clone git@github.com:milarobotlearningcourse/cleanrl.git`
1. `cd cleanrl`
1. `poetry install`
1. `poetry install -E pybullet`


## Examples: 

1. `poetry run python cleanrl/ppo.py --seed 1 --env-id CartPole-v0 --total-timesteps 50000`

1. `poetry run python cleanrl/ppo_continuous_action.py     --seed 1     --env-id MinitaurBulletDuckEnv-v0     --total-timesteps 50000 --cuda false`
1. `poetry run python cleanrl/ppo_continuous_action.py     --seed 1     --env-id MinitaurBulletDuckEnv-v0     --total-timesteps 50000 --cuda false --capture-video true` 