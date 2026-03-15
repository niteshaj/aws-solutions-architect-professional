# Load Balancer Types

## Overview
AWS provides three types of load balancers to distribute incoming application traffic across multiple targets.

## Application Load Balancer (ALB)
- **Layer 7**: HTTP/HTTPS traffic
- **Path-based routing**: Route based on URL path
- **Host-based routing**: Route based on hostname
- **Container support**: Native ECS/EKS integration

## Network Load Balancer (NLB)
- **Layer 4**: TCP/UDP traffic
- **High performance**: Ultra-low latency
- **Static IP**: Preserve source IP
- **TLS termination**: Optional encryption

## Gateway Load Balancer (GWLB)
- **Layer 3**: Network traffic
- **Appliance delivery**: Virtual appliance integration
- **Transparent**: No changes to applications
- **Scale-out**: Auto-scaling for appliances

## Use Cases

### ALB Best For
- Web applications
- Microservices
- Container-based applications
- Content-based routing

### NLB Best For
- TCP/UDP applications
- High-performance requirements
- Static IP needs
- IoT and gaming

### GWLB Best For
- Network security appliances
- Intrusion detection
- Firewalls
- Traffic inspection

## Benefits
- High availability
- Automatic scaling
- Health monitoring
- Cost optimization
