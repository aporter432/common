# Service Analysis Template

## 1. Service Overview
- [ ] Service name and primary purpose
- [ ] Key responsibilities (list specific functions)
- [ ] External dependencies (APIs, services)
- [ ] Internal dependencies (other microservices)
- [ ] Current integration points

## 2. Configuration Analysis
### 2.1 Nginx Configuration
- [ ] Service-specific routes (list all endpoints)
- [ ] Custom headers
- [ ] Special proxy requirements
- [ ] Security requirements
- [ ] CORS settings
- [ ] Rate limiting
- [ ] Load balancing
- [ ] SSL/TLS requirements

### 2.2 Docker Configuration
- [ ] Required services (list with versions)
- [ ] Volume mounts (specify read/write)
- [ ] Environment variables (categorize by purpose)
- [ ] Network configuration
- [ ] Health checks (all services)
- [ ] Resource limits
- [ ] Development vs Production differences

### 2.3 Application Configuration
- [ ] Environment variables (list all)
- [ ] Configuration files (location and purpose)
- [ ] Secrets management
- [ ] Feature flags
- [ ] Logging configuration
- [ ] Monitoring setup
- [ ] Development vs Production settings

## 3. Dependencies
### 3.1 Infrastructure
- [ ] Databases (specify version and purpose)
- [ ] Cache layers (configuration details)
- [ ] Message queues (usage patterns)
- [ ] Storage requirements (estimate size)
- [ ] External services (integration details)
- [ ] Scaling requirements

### 3.2 Common Module Usage
- [ ] Authentication (methods used)
- [ ] Logging (formats and destinations)
- [ ] Shared utilities (list specific uses)
- [ ] Configuration patterns
- [ ] Common middleware
- [ ] Potential new common components

## 4. API Interface
- [ ] Endpoints exposed (full list with methods)
- [ ] Authentication methods
- [ ] Request/Response formats
- [ ] Error handling patterns
- [ ] Rate limiting rules
- [ ] Documentation location
- [ ] API versioning strategy

## 5. Testing Infrastructure
- [ ] Test types (unit, integration, e2e)
- [ ] Test configuration
- [ ] Mock services
- [ ] Test data management
- [ ] CI/CD requirements
- [ ] Test coverage requirements
- [ ] Performance test setup

## 6. Monitoring & Logging
- [ ] Metrics collected (list specific metrics)
- [ ] Log formats (specify for each type)
- [ ] Alert configurations
- [ ] Health check endpoints
- [ ] Performance monitoring
- [ ] Tracing setup
- [ ] Dashboard requirements

## 7. Security
- [ ] Authentication methods (all types)
- [ ] Authorization rules
- [ ] Security headers
- [ ] SSL/TLS configuration
- [ ] Rate limiting
- [ ] Input validation
- [ ] Security scanning requirements

## 8. Development Tools
- [ ] Build tools (versions)
- [ ] Linting configuration
- [ ] Code formatting
- [ ] Development utilities
- [ ] Local development setup
- [ ] Required developer tools
- [ ] Development workflow

## 9. Separation Analysis
### 9.1 Components to Keep
- [ ] Service-specific configurations
- [ ] Unique business logic
- [ ] Special requirements
- [ ] Custom implementations
- [ ] Essential integrations

### 9.2 Components to Move to Common
- [ ] Shared configurations
- [ ] Common patterns
- [ ] Reusable utilities
- [ ] Standard middleware
- [ ] Documentation templates

### 9.3 Components to Remove
- [ ] Deprecated features
- [ ] Unused configurations
- [ ] Redundant implementations
- [ ] Legacy code
- [ ] Unnecessary dependencies

## 10. Migration Plan
- [ ] Dependencies to update (list versions)
- [ ] Configuration changes (specify each)
- [ ] Testing requirements
- [ ] Deployment considerations
- [ ] Rollback plan
- [ ] Migration timeline
- [ ] Testing strategy

## 11. Documentation Needs
- [ ] API documentation
- [ ] Configuration guide
- [ ] Development setup
- [ ] Deployment guide
- [ ] Troubleshooting guide
- [ ] Architecture diagrams
- [ ] Integration guides

## 12. Lessons Learned
- [ ] Challenges encountered
- [ ] Solutions implemented
- [ ] Improvements made
- [ ] Future considerations
- [ ] Team feedback 