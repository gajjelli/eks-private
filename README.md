# eks-private

find . -type f -name "*.tf" -exec sed -i'' -e 's/1.0.9/1.1.0/g' {} +
