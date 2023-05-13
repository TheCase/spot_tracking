
# Summary

  Presents the last 60 days (from last pull) of AWS Spot Instance Pricing and made availble via Grafana Dashboard

# Prerequisites

  - docker-compose

# Running

```
git clone https://github.com/TheCase/spot_cost_tracker && \
docker-compose up -d && \
echo "waiting 5 seconds..." && \
sleep 5 && \
open http://localhost:3000/d/b43004f1-b1bc-4842-8ec5-587860641ae4/spot-pricing-last-60d?orgId=1
```
