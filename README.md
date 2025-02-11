# Kubernetes Cluster Deployment

This repository contains configurations and scripts for deploying a Kubernetes cluster using Talos OS. The deployment is designed for both production and development environments, utilizing various hardware and cloud resources.

## Technologies Used

- **Kubernetes**: An open-source platform for automating deployment, scaling, and operations of application containers across clusters of hosts.
- **Talos OS**: A modern Linux distribution optimized for secure and minimal Kubernetes deployments.
- **Hetzner Cloud**: Used for hosting and managing Kubernetes clusters.
- **Beelink S12 Pro N100**: Three units serve as production nodes.
- **Synology DS918+**: Utilized for production media storage.
- **Oracle Cloud Free Tier**: Employed for development purposes.

## Repository Structure

The repository is organized as follows:

- `kubernetes/`: Contains Kubernetes manifests and configurations.
- `.gitignore`: Specifies files and directories to be ignored by Git.
- `README.md`: This file, providing an overview of the project.

## Getting Started

To set up the Kubernetes cluster:

1. **Clone the Repository**:

   ```bash
   git clone https://github.com/nmourapt/k8s.git
   cd k8s
   ```

2. **Review Configuration Files:**

Ensure that the configurations in the kubernetes/ directory align with your environment and requirements.

3. **Deploy the Cluster:**

Follow the deployment instructions provided in the kubernetes/ directory to initialize and configure your cluster.

## Contributing
Contributions are welcome! Please fork the repository and submit a pull request with your proposed changes.

## License
This project is licensed under the MIT License.
