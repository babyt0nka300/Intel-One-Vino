wget https://apt.repos.intel.com/intel-gpg-keys/GPG-PUB-KEY-INTEL-SW-PRODUCTS.PUB

sudo apt-key add GPG-PUB-KEY-INTEL-SW-PRODUCTS.PUB

echo "deb https://apt.repos.intel.com/openvino/2024 ubuntu20 main" | sudo tee /etc/apt/sources.list.d/intel-openvino-2024.list

echo "deb https://apt.repos.intel.com/openvino/2024 ubuntu22 main" | sudo tee /etc/apt/sources.list.d/intel-openvino-2024.list

echo "deb https://apt.repos.intel.com/openvino/2024 ubuntu24 main" | sudo tee /etc/apt/sources.list.d/intel-openvino-2024.list

sudo apt update

apt-cache search openvino

sudo apt install openvino-2024.4.0

# Intel-One-Vino
