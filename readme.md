# Velero 

# 실행 명령어

## 1. Install
```bash
ansible-playbook playbooks/1_install.yml
```

## 2. 백업
```bash
ansible-playbook playbooks/2_backup.yml
```

## 3. ns 삭제
```bash
ansible-playbook playbooks/3_delete.yml
```

## 4. 복구
```bash
ansible-playbook playbooks/4_restore.yml
```

## 5. 전체 실행
```bash
ansible-playbook playbooks/site.yml
```
