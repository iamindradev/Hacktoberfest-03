
class Solution {
public:
    ListNode *getIntersectionNode(ListNode *headA, ListNode *headB) {
        
        if(!headA or !headB) return NULL;
        ListNode* a = headA;
        ListNode* b = headB;
        
        while(a != b){
            a = (!a) ? headB : a->next;
            b = (!b) ? headA : b->next;
        }
        return a;
    }
};
