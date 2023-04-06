# C++ code for Root-Equals-Sum-of-Children(Binary Tree Question)

class Solution {
public:
    bool checkTree(TreeNode* root)
    {
    if(root->val==root->left->val+root->right->val)
    {
        return true;
    }
return false;   
    }};
        
